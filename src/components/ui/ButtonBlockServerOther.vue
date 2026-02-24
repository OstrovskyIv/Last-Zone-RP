<template>
  <div
    @click="scrollToHowToStart"
    @keydown.enter="scrollToHowToStart"
    @keydown.space.prevent="scrollToHowToStart"
    role="button"
    tabindex="0"
    class="bg-transparent cursor-pointer inline-block focus:outline-none focus:ring-2 focus:ring-[#966EA2] focus:ring-offset-2 focus:ring-offset-transparent rounded transition-all"
  >
    <p class="text-white max-w-[250px] text-[16px] sm:text-[20px] md:text-[24px] lg:text-[28px] xl:text-[30px] pt-20 leading-none border-[#966EA2] border-b-6 w-[200px] md:w-[300px] text-center mx-auto">
      Узнать больше:
    </p>
  </div>
</template>

<script setup lang="ts">
const scrollToHowToStart = () => {
  const element = document.getElementById('how-to-start');
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' });
  }
};
</script>
