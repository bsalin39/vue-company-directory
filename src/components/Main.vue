<script setup>
  import MainSearch from './MainSearch.vue'
</script>

<template>
  <div class="wrapper">
    <MainSearch />
    <h1>Hello There</h1>
  </div>
</template>

<style scoped lang="postcss">
  .wrapper {
    @apply flex h-screen flex-col items-center justify-center;
  }
</style>
