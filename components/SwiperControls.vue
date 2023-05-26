<script setup lang="ts">
const swiper = useSwiper();
</script>

<template>
  <div class="relative bottom-20 flex flex-row justify-between px-2">
    <button
      @click="swiper.slidePrev()"
      class="rounded-full bg-pink-400 px-2 py-1 text-xl"
    >
      ←</button
    ><button
      @click="swiper.slideNext()"
      class="rounded-full bg-blue-500 px-2 py-1 text-xl"
    >
      →
    </button>
  </div>
</template>

<style>
button {
  z-index: 100;
}
</style>
