<template>
  <div class="header">
    <h1 class="title">{{ title }}</h1>
  </div>
</template>
<script setup lang="ts">
  const title = ref<string>("Hello World!!");
</script>
<style scoped lang="scss">
.header {
  display: flex;
  justify-content: center;
  align-items: center;
  .title {
    font-weight: bold;
    font-size: 32px;
  }
}
</style>