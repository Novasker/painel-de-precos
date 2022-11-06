<template>
  <div class="component-container">
    <span class="component-text">{{ text }}</span>
  </div>
</template>

<script>
export default {
  name: 'AppComponent',
  props: {
    text: {
      type: String,
      default: 'Imperdível',
    },
  },
}
</script>

<style scoped>
.component-container {
  display: flex;
  position: relative;
}
.component-text {
  color: var(--dl-color-gray-white);
  z-index: 100;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
</style>
