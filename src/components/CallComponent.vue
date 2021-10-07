<script setup>
import * as Test from './OutsideComponent.vue'
console.log(Test.default.components.InsideComponent)
</script>
<template>
<div>
  <Test.default></Test.default>
  <br/>
  <Test.default.components.InsideComponent>Passed from Call Component</Test.default.components.InsideComponent>
</div>
</template>

<style scoped></style>