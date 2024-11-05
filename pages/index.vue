<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <div>
    <h1>Page: 首頁</h1>
    <p>目前路由的路徑 - route.fullPath為 :{{ route.fullPath }}</p>
    <div class="d-flex">
      <button type="button" class="btn btn-primary">Primary</button>
      <button type="button" class="btn btn-secondary">Secondary</button>
      <button type="button" class="btn btn-success">Success</button>
      <button type="button" class="btn btn-danger">Danger</button>
      <button type="button" class="btn btn-warning">Warning</button>
      <button type="button" class="btn btn-info">Info</button>
      <button type="button" class="btn btn-light">Light</button>
      <button type="button" class="btn btn-dark">Dark</button>
      <button type="button" class="btn btn-link">Link</button>
    </div>
  </div>
</template>

<style scoped></style>
