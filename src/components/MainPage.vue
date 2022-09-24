<script setup>
  import MainSearch from '@/components/MainSearch.vue'
  import MainCards from '@/components/MainCards.vue'
  import MainPaginagion from '@/components/MainPagination.vue'
</script>

<template>
  <div class="wrapper">
    <MainSearch />
    <MainCards />
    <MainPaginagion />
  </div>
</template>

<style scoped lang="postcss">
  .wrapper {
    @apply container mx-auto flex flex-col gap-4 py-4;
  }
</style>
