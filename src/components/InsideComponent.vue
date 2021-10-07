<template>
<div class="inner">
  <slot></slot>
</div>
</template>
<script>
export default {
  name: "InsideComponent"
}
</script>
<style scoped>
.inner {
  font-weight: bold;
  color: darkred;
}
</style>