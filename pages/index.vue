<script setup lang="ts">
const route = useRoute();
</script>

<template>
  <div>
    <h1>Page: 首頁</h1>
    <p>目前路由的路徑 - route.fullPath為 :{{ route.fullPath }}</p>
    <div class="d-flex gap-2">
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
    <h2>產品</h2>
    <Card imageSrc="https://raw.githubusercontent.com/hexschool/2022-web-layout-training/main/typescript-hotel/%E6%A1%8C%E6%A9%9F%E7%89%88/room2-1.png"
      altText="享受高級的住宿體驗，尊爵雙人房提供給您舒適寬敞的空間和精緻的裝潢"
      title="尊爵雙人房"
      price="NT$10000"
      buttonText="馬上預約"
      />
  </div>
</template>

<style scoped></style>
