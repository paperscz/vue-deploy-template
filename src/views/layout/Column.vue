<template>
  <div class="page-column">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'PageColumn'
}
</script>

<style scoped>
.page-column {
  display: flex;
  flex-grow: 1;
  flex-direction: column;
}
</style>
