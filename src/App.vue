<template>
 <div class="app">
   <the-header />
   <the-volume-button />
   <watch />
  <category-items />
 </div>
</template>

<script>

export default {
  name: 'App',
  components: {
    TheHeader: () => import('@/layouts/TheHeader.vue'),
    TheVolumeButton: () => import('@/layouts/TheVolumeButton.vue'),
    Watch: () => import('@/components/Watch.vue'),
    CategoryItems: () => import('@/components/CategoryItems.vue'),
  }
};
</script>

<style scoped>
.app {
  min-height: 100vh;
}


</style>
