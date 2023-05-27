<template>
  <router-view></router-view>
</template>
<script setup lang="ts">
const route = useRoute();
nextTick(() => {
  console.log(765, route);
});
</script>

<style></style>
