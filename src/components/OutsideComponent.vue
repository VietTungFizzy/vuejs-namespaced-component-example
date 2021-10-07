<template>
<div>
  <div><strong>This is outside component</strong></div>
  <br/>
  <InsideComponent>Inside</InsideComponent>
</div>
</template>
<script>
import InsideComponent from "./InsideComponent.vue"
export default {
  name: "OutsideComponent",
  components: {
    InsideComponent
  }
}
</script>
<style scoped></style>