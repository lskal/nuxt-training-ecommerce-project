<script setup lang="ts">
const route = useRoute();
const slug = computed(() => String(route.params.slug));
</script>

<template>
  <div class="container">
    <h1>Product: {{ slug }}</h1>
  </div>
</template>

<style scoped lang="scss">
.container {
  padding-left: var(--page-gutter);
  padding-right: var(--page-gutter);
}
</style>
