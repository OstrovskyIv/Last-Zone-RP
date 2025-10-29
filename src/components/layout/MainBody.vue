<template>
  <div class="flex justify-center items-center gap-8 lg:gap-20 xl:gap-10 2xl:gap-30 min-h-screen bg-[#19181D] flex-col xl:flex-row pt-10 xl:pt-0">
    <!-- картинка лево-верх -->
    <div class="w-[910px] sm:w-[500px] xl:w-[910px] pl-0 lg:pl-[30px] xl:pl-[40px] 2xl:pl-[50px]">
      <img src="/public/images/ServerSectionBackground.png" alt="ServerSectionBackground" class="w-full h-full"/>
    </div>

    <!--Блок справа-низ -->
    <div class="flex flex-col items-center text-center pr-0 lg:pr-[30px] xl:pr-[40px] 2xl:pr-[50px]">

      <h6 class="text-[#966EA2] font-Caprasimo max-w-[810px] text-[16px] sm:text-[20px] md:text-[24px] lg:text-[28px] xl:text-[30px] leading-[20px] sm:leading-[24px] md:leading-[28px] lg:leading-[32px] xl:leading-[34px]">
        Мы - команда энтузиастов, которая любит
        <span class="font-bold">STALKER</span>
      </h6>

      <h2 class="text-white font-capture-it max-w-[457px] text-[40px] sm:text-[50px] md:text-[60px] lg:text-[70px] xl:text-[80px] 2xl:text-[90px] leading-[60px] sm:leading-[80px] md:leading-[100px] lg:leading-[140px] xl:leading-[180px] 2xl:leading-[220px]">
        О СЕРВЕРЕ
      </h2>

      <p class="text-white font-Caprasimo max-w-[810px] text-[14px] sm:text-[16px] md:text-[20px] lg:text-[24px] xl:text-[28px] 2xl:text-[30px] leading-[18px] sm:leading-[20px] md:leading-[24px] lg:leading-[26px] xl:leading-[28px] 2xl:leading-[30px]">
        Используя наиболее подходящую карту и <br/>
        модификации, мы постарались сделать наиболее <br/>
        близкий к той самой атмосфере ЧЗО
        <span class="font-bold">RP</span>
        сервер. Наши <br/> админы и кураторы тщательно следят за <br/>
        соблюдением правил, администрация всегда на связи <br/> и готова помочь игрокам.<br/>
        Мы не добавляли моды, которые могут как-то <br/> нарушить и испортить вайб сталкерства.
        Если ты <br/> любишь Сталкер РП - тебе к нам!
      </p>

      <div class="flex justify-center items-center sm:gap-20 md:gap-30 lg:gap-40 xl:gap-50 2xl:gap-60">
        <ButtonBlockServerDS />
        <ButtonBlockServerOther />
      </div>
    </div>
  </div>

  <div class="min-h-screen flex flex-col justify-between py-7 px-4 sm:px-2 md:px-8 lg:px-12 xl:px-16 2xl:px-5">
    <h6 class="flex flex-col text-center xl:text-start xl:pl-[60px] text-white font-capture-it text-[40px] sm:text-[50px] md:text-[60px] lg:text-[70px] xl:text-[80px] 2xl:text-[90px]">
      КАК НАЧАТЬ ИГРАТЬ?
    </h6>
    <div class="flex flex-col items-center justify-center xl:flex-row">
      <!-- ШАГ 1 -->
      <div class="relative">
        <img src="/public/images/BackgroundGameSection.png" alt="ServerSectionBackground" class="sm:w-[311px] md:w-[350px] lg:w-[380px] xl:w-[400px] 2xl:w-[411px]"/>
        <div class="absolute inset-0 flex flex-col items-center justify-between py-5">
          <h3 class="text-[#966EA2] sm:text-[60px] md:text-[70px] lg:text-[70px] xl:text-[80px] 2xl:text-[100px]">1</h3>
          <span class="text-white text-[14px] sm:text-[25px] md:text-[30px] lg:text-[30px] xl:text-[20px] 2xl:text-[20px] text-3xl-30 text-center">Посетите наш Discord- <br/> сервер, где вы сможете <br/> найти ЛОР, правила, а <br/> также пообщаться с игроками</span>
          <ButtonGoOne />
        </div>
      </div>
      <!-- Стрелка 1 -->
      <img src="/public/images/Arrows.png" alt="Arrows" class="sm:w-[287px] sm:h-[250px] md:w-[287px] md:h-[250px] lg:w-[287px] lg:h-[250px] xl:w-[160px] xl:h-[130px] 2xl:w-[287px] 2xl:h-[192px] rotate-90 xl:rotate-0"/>
      <!-- ШАГ 2 -->
      <div class="relative">
        <img src="/public/images/BackgroundGameSection.png" alt="ServerSectionBackground" class="sm:w-[311px] md:w-[350px] lg:w-[380px] xl:w-[400px] 2xl:w-[411px]"/>
        <div class="absolute inset-0 flex flex-col items-center justify-between py-5">
          <h3 class="text-[#966EA2] sm:text-[60px] md:text-[70px] lg:text-[70px] xl:text-[80px] 2xl:text-[100px]">2</h3>
          <span class="text-white text-[14px] sm:text-[25px] md:text-[30px] lg:text-[30px] xl:text-[20px] 2xl:text-[20px] text-3xl-30 text-center">Подпишитесь на наши <br/> модификации в Steam и <br/> скачайте их</span>
          <ButtonGoTwo />
        </div>
      </div>
        <!-- Стрелка 2 -->
        <img src="/images/Arrows.png" alt="Arrows" class="sm:w-[287px] sm:h-[250px] md:w-[287px] md:h-[250px] lg:w-[287px] lg:h-[250px] xl:w-[160px] xl:h-[130px] 2xl:w-[287px] 2xl:h-[192px] rotate-90 xl:rotate-0"/>
        <!-- ШАГ 3 -->
        <div class="relative flex sm:flex-col">
          <img src="/public/images/BackgroundGameSection.png" alt="ServerSectionBackground" class="sm:w-[311px] md:w-[350px] lg:w-[380px] xl:w-[400px] 2xl:w-[411px]"/>
          <div class="absolute inset-0 flex flex-col items-center justify-between py-5">
            <h3 class="text-[#966EA2] sm:text-[60px] md:text-[70px] lg:text-[70px] xl:text-[80px] 2xl:text-[100px]">3</h3>
            <span class="text-white text-[14px] sm:text-[25px] md:text-[30px] lg:text-[30px] xl:text-[20px] 2xl:text-[20px] text-3xl-30 text-center">Отправляйтесь в <br/> Чернобыльскую Зону <br/> Отчуждения. Изучайте, <br/> общайтесь,<br/> погружайтесь</span>
            <ButtonGoThree />
          </div>
        </div>
    </div>
    <p class="flex justify-center text-white text-[14px] sm:text-[16px] md:text-[20px] lg:text-[24px] xl:text-[28px] 2xl:text-[30px] text-center">
      Данная памятка носит ознакомительный характер. Если вы уже играли в РП, то вам не составит проблем подключиться к нашему серверу, однако рекомендуем ознакомиться с правилами и ЛОРом перед началом игры.
    </p>
  </div>

  <section class="min-h-screen py-7 px-4 sm:px-2 md:px-8 lg:px-12 xl:px-16 2xl:px-5">
    <h6 class="text-white font-capture-it 2xl:pl-[60px] 2xl:text-[90px]">
      ГАЛЕРЕЯ
    </h6>
    <div class="grid grid-cols-3 place-items-center px-5 py-6">
      <div class="flex flex-col gap-18">
        <div class="flip-card w-[624px] h-[351px]" @mouseenter="flipLeftTop" @mouseleave="unflipLeftTop">
          <div class="flip-card-inner relative w-full h-full transition-transform duration-600" :class="{ 'flipped': isFlippedLeftTop }">
            <div class="flip-card-front absolute inset-0">
              <img src="/public/images/GallerySectionOne/GallerySection1_2.png" alt="GallerySection1_2" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
            <div class="flip-card-back absolute inset-0">
              <img src="/public/images/GallerySectionTwo/GallerySection2_2.png" alt="GallerySection2_2" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
        <div class="flip-card w-[624px] h-[351px]" @mouseenter="flipLeftDown" @mouseleave="unflipLeftDown">
          <div class="flip-card-inner relative w-full h-full transition-transform duration-600" :class="{ 'flipped': isFlippedLeftDown }">
            <div class="flip-card-front absolute inset-0">
              <img src="/public/images/GallerySectionOne/GallerySection1_3.png" alt="GallerySection1_3" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>

            <div class="flip-card-back absolute inset-0">
              <img src="/public/images/GallerySectionTwo/GallerySection2_3.png" alt="GallerySection2_3" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
      </div>
      <div class="flip-card w-[444px] h-[772px]" @mouseenter="flipCenter" @mouseleave="unflipCenter">
        <div class="flip-card-inner relative w-full h-full transition-transform duration-600" :class="{ 'flipped': isFlippedCenter }">
          <div class="flip-card-front absolute inset-0">
            <img src="/public/images/GallerySectionOne/GallerySection1_1.png" alt="GallerySection1_2" class="2xl:w-[444px] 2xl:h-[772px]"/>
          </div>
          <div class="flip-card-back absolute inset-0">
            <img src="/public/images/GallerySectionTwo/GallerySection2_1.png" alt="GallerySection2_2" class="2xl:w-[444px] 2xl:h-[772px]"/>
          </div>
        </div>
      </div>
      <div class="flex flex-col gap-18">
        <div class="flip-card w-[624px] h-[351px]" @mouseenter="flipRightTop" @mouseleave="unflipRightTop">
          <div class="flip-card-inner relative w-full h-full transition-transform duration-600" :class="{ 'flipped': isFlippedRightTop }">
            <div class="flip-card-front absolute inset-0">
              <img src="/public/images/GallerySectionOne/GallerySection1_4.png" alt="GallerySection1_4" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
            <div class="flip-card-back absolute inset-0">
              <img src="/public/images/GallerySectionTwo/GallerySection2_4.png" alt="GallerySection2_4" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
        <div class="flip-card w-[624px] h-[351px]" @mouseenter="flipRightDown" @mouseleave="unflipRightDown">
          <div class="flip-card-inner relative w-full h-full transition-transform duration-600" :class="{ 'flipped': isFlippedRightDown }">
            <div class="flip-card-front absolute inset-0">
              <img src="/public/images/GallerySectionOne/GallerySection1_5.png" alt="GallerySection1_5" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>

            <div class="flip-card-back absolute inset-0">
              <img src="/public/images/GallerySectionTwo/GallerySection2_5.png" alt="GallerySection2_5" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue'
import ButtonBlockServerDS from '@/components/ui/ButtonBlockServerDS.vue'
import ButtonBlockServerOther from '@/components/ui/ButtonBlockServerOther.vue'
import ButtonGoOne from '@/components/ui/ButtonGoOne.vue'
import ButtonGoTwo from '@/components/ui/ButtonGoTwo.vue'
import ButtonGoThree from '@/components/ui/ButtonGoThree.vue'
const isFlippedCenter = ref(false);
const isFlippedLeftTop = ref(false);
const isFlippedLeftDown = ref(false);
const isFlippedRightTop = ref(false);
const isFlippedRightDown = ref(false);
const flipCenter = () => {
  isFlippedCenter.value = true; // Только переворачивает
}
const unflipCenter = () => {
  isFlippedCenter.value = false; // Только возвращает обратно
}
const flipLeftTop = () => {
  isFlippedLeftTop.value = true;
}
const unflipLeftTop = () => {
  isFlippedLeftTop.value = false;
}
const flipLeftDown = () => {
  isFlippedLeftDown.value = true;
}
const unflipLeftDown = () => {
  isFlippedLeftDown.value = false;
}
const flipRightTop = () => {
  isFlippedRightTop.value = true;
}
const unflipRightTop = () => {
  isFlippedRightTop.value = false;
}
const flipRightDown = () => {
  isFlippedRightDown.value = true;
}
const unflipRightDown = () => {
  isFlippedRightDown.value = false;
}
</script>

<style scoped>
/* Основной контейнер - задает перспективу */
.flip-card {
  perspective: 1000px;
}

/* Внутренний блок - осуществляет переворот */
.flip-card-inner {
  transform-style: preserve-3d;
  transition: transform 0.6s;
}

/* Состояние перевернутой карточки */
.flip-card-inner.flipped {
  transform: rotateY(180deg);
}

/* Общие стили для обеих сторон */
.flip-card-front,
.flip-card-back {
  backface-visibility: hidden;
}

/* Задняя сторона изначально повернута */
.flip-card-back {
  transform: rotateY(180deg);
}
</style>
