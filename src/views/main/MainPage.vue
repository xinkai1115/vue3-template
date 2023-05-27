<script setup lang="ts">
import { onMounted } from "vue";
import { gsap } from "gsap";
onMounted(() => {
  const tl = gsap.timeline();
  // 把tween动画添加到timeline实例上，注意我们在用的是tl.to 而不是gsap.to
  tl.to(".green", { x: 600, duration: 2 }, 1);
  tl.to(".purple", { x: 600, duration: 1, delay: 1 });
  tl.to(".orange", { x: 600, duration: 1 });
});
</script>
<template>
  <div class="green box">asdf asdfas asdfsa</div>
  <div class="purple box"></div>
  <div class="orange box"></div>
</template>
<style scoped>
body {
  background: #1d1d1d;
}
.quote {
  font-family: helvetica;
  font-weight: 300;
  font-size: 15vw;
  text-transform: uppercase;
}
.box {
  width: 100px;
  height: 100px;
}
.green {
  background-color: green;
}
.purple {
  background-color: purple;
}
.orange {
  background-color: orange;
}
</style>
