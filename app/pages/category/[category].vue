<script setup lang="ts">
const route = useRoute();
const category = computed(() => String(route.params.category));
</script>

<template>
  <div class="container">
    <h1>Category: {{ category }}</h1>
  </div>
</template>

<style scoped lang="scss">
.container {
  padding-left: var(--page-gutter);
  padding-right: var(--page-gutter);
}
</style>
