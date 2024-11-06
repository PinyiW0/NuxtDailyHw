<script setup lang="ts">
const menuList: any[] = [
  { label: "前台首頁", path: "/"},
  { label: "前台About", path: "/about"},
  { label: "後台首頁", path: "/admin"},
  { label: "後台訂單", path: "/admin/order"},
]
</script>

<template>
  <div class="p-5 overflow-hidden">
    <header>
      <div class="d-flex items-center justify-center gap-2">
        <NuxtLink v-for="(item, idx) in menuList" :key="idx" :to="item.path" :title="item.label">
          <p>{{ item.label }}</p>
        </NuxtLink>
      </div>
    </header>
    <slot />
    <footer>default footer</footer>
  </div>
</template>

<style scoped></style>
