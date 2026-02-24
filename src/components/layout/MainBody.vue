<template>
  <!-- О СЕРВЕРЕ -->
  <div class="flex justify-center items-center gap-8 lg:gap-20 xl:gap-10 2xl:gap-30 min-h-screen bg-[#19181D] flex-col xl:flex-row pt-10 xl:pt-0">
    <!-- картинка лево-верх -->
    <div class="w-[910px] sm:w-[500px] xl:w-[910px] pl-0 lg:pl-[30px] xl:pl-[40px] 2xl:pl-[50px]">
      <img src="/images/ServerSectionBackground.png" alt="ServerSectionBackground" class="w-full h-full"/>
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
  <!-- КАК НАЧАТЬ ИГРАТЬ -->
  <div id="how-to-start" class="min-h-screen flex flex-col justify-between py-7 px-4 sm:px-2 md:px-8 lg:px-12 xl:px-16 2xl:px-5">
    <h6 class="flex flex-col text-center xl:text-start xl:pl-[60px] text-white font-capture-it text-[40px] sm:text-[50px] md:text-[60px] lg:text-[70px] xl:text-[80px] 2xl:text-[90px]">
      КАК НАЧАТЬ ИГРАТЬ?
    </h6>
    <div class="flex flex-col items-center justify-center xl:flex-row">
      <!-- ШАГ 1 -->
      <div class="relative">
        <img src="/images/BackgroundGameSection.png" alt="ServerSectionBackground" class="sm:w-[311px] md:w-[350px] lg:w-[380px] xl:w-[400px] 2xl:w-[411px]"/>
        <div class="absolute inset-0 flex flex-col items-center justify-between py-5">
          <h3 class="text-[#966EA2] sm:text-[60px] md:text-[70px] lg:text-[70px] xl:text-[80px] 2xl:text-[100px]">1</h3>
          <span class="text-white text-[14px] sm:text-[25px] md:text-[30px] lg:text-[30px] xl:text-[20px] 2xl:text-[20px] text-3xl-30 text-center">Посетите наш Discord- <br/> сервер, где вы сможете <br/> найти ЛОР, правила, а <br/> также пообщаться с игроками</span>
          <ButtonGoOne />
        </div>
      </div>
      <!-- Стрелка 1 -->
      <img src="/images/Arrows.png" alt="Arrows" class="sm:w-[287px] sm:h-[250px] md:w-[287px] md:h-[250px] lg:w-[287px] lg:h-[250px] xl:w-[160px] xl:h-[130px] 2xl:w-[287px] 2xl:h-[192px] rotate-90 xl:rotate-0"/>
      <!-- ШАГ 2 -->
      <div class="relative">
        <img src="/images/BackgroundGameSection.png" alt="ServerSectionBackground" class="sm:w-[311px] md:w-[350px] lg:w-[380px] xl:w-[400px] 2xl:w-[411px]"/>
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
          <img src="/images/BackgroundGameSection.png" alt="ServerSectionBackground" class="sm:w-[311px] md:w-[350px] lg:w-[380px] xl:w-[400px] 2xl:w-[411px]"/>
          <div class="absolute inset-0 flex flex-col items-center justify-between py-5">
            <h3 class="text-[#966EA2] sm:text-[60px] md:text-[70px] lg:text-[70px] xl:text-[80px] 2xl:text-[100px]">3</h3>
            <span class="text-white text-[14px] sm:text-[25px] md:text-[30px] lg:text-[30px] xl:text-[20px] 2xl:text-[20px] text-3xl-30 text-center">Отправляйтесь в <br/> Чернобыльскую Зону <br/> Отчуждения. Изучайте, <br/> общайтесь,<br/> погружайтесь</span>
            <div class="flex items-center justify-center">
              <ButtonGoThree />
            </div>
          </div>
        </div>
    </div>
    <p class="flex justify-center text-white text-[14px] sm:text-[16px] md:text-[20px] lg:text-[24px] xl:text-[28px] 2xl:text-[30px] text-center">
      Данная памятка носит ознакомительный характер. Если вы уже играли в РП, то вам не составит проблем подключиться к нашему серверу, однако рекомендуем ознакомиться с правилами и ЛОРом перед началом игры.
    </p>
  </div>
  <!-- ГАЛЕРЕЯ -->
  <section class="2xl:min-h-screen py-7 px-4 sm:px-2 md:px-8 lg:px-12 xl:px-16 2xl:px-5">
    <div class="sm:flex sm:flex-col sm:items-center md:flex md:flex-col md:items-center lg:block 2xl:pl-[60px] 2xl:max-w-[400px]">
      <p class="text-white font-capture-it text-center lg:text-start sm:text-[60px] 2xl:text-[90px] leading-none">
        ГАЛЕРЕЯ
      </p>
      <div class="h-2 bg-[#966EA2] border-0 sm:w-63 md:w-63 lg:w-62 xl:w-62 2xl:w-93 sm:mx-auto md:mx-auto"></div>
    </div>
    <div class="grid grid-cols-1 3xl:grid-cols-3 place-items-center px-10 py-20 sm:gap-5 md:gap-6 ">
      <div class="flex flex-row 3xl:flex-col sm:gap-7 2xl:gap-18">
        <div class="flip-card sm:w-[280px] sm:h-[158px] md:w-[350px] md:h-[197px] lg:w-[480px] lg:h-[270px] xl:w-[580px] xl:h-[327px] 2xl:w-[624px] 2xl:h-[351px]" @mouseenter="flip('leftTop')" @mouseleave="unflip('leftTop')">
          <div class="flip-card-inner relative w-full h-full" :class="{ 'flipped': flipStates.leftTop }">
            <div class="flip-card-front absolute inset-0">
              <img src="/images/GallerySectionOne/GallerySection1_2.png" alt="GallerySection1_2" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
            <div class="flip-card-back absolute inset-0">
              <img src="/images/GallerySectionTwo/GallerySection2_2.png" alt="GallerySection2_2" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
        <div class="flip-card sm:w-[280px] sm:h-[158px] md:w-[350px] md:h-[197px] lg:w-[480px] lg:h-[270px] xl:w-[580px] xl:h-[327px] 2xl:w-[624px] 2xl:h-[351px]" @mouseenter="flip('leftDown')" @mouseleave="unflip('leftDown')">
          <div class="flip-card-inner relative w-full h-full" :class="{ 'flipped': flipStates.leftDown }">
            <div class="flip-card-front absolute inset-0">
              <img src="/images/GallerySectionOne/GallerySection1_3.png" alt="GallerySection1_3" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
            <div class="flip-card-back absolute inset-0">
              <img src="/images/GallerySectionTwo/GallerySection2_3.png" alt="GallerySection2_3" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
      </div>
      <div class="flip-card 3xl:w-[444px] 3xl:h-[772px] hidden 3xl:block" @mouseenter="flip('center')" @mouseleave="unflip('center')">
        <div class="flip-card-inner relative w-full h-full" :class="{ 'flipped': flipStates.center }">
          <div class="flip-card-front absolute inset-0">
            <img src="/images/GallerySectionOne/GallerySection1_1.png" alt="GallerySection1_2" class="2xl:w-[444px] 2xl:h-[772px]"/>
          </div>
          <div class="flip-card-back absolute inset-0">
            <img src="/images/GallerySectionTwo/GallerySection2_1.png" alt="GallerySection2_2" class="2xl:w-[444px] 2xl:h-[772px]"/>
          </div>
        </div>
      </div>
      <div class="flex flex-row 3xl:flex-col sm:gap-7 2xl:gap-18">
        <div class="flip-card sm:w-[280px] sm:h-[158px] md:w-[350px] md:h-[197px] lg:w-[480px] lg:h-[270px] xl:w-[580px] xl:h-[327px] 2xl:w-[624px] 2xl:h-[351px]" @mouseenter="flip('rightTop')" @mouseleave="unflip('rightTop')">
          <div class="flip-card-inner relative w-full h-full" :class="{ 'flipped': flipStates.rightTop }">
            <div class="flip-card-front absolute inset-0">
              <img src="/images/GallerySectionOne/GallerySection1_4.png" alt="GallerySection1_4" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
            <div class="flip-card-back absolute inset-0">
              <img src="/images/GallerySectionTwo/GallerySection2_4.png" alt="GallerySection2_4" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
        <div class="flip-card sm:w-[280px] sm:h-[158px] md:w-[350px] md:h-[197px] lg:w-[480px] lg:h-[270px] xl:w-[580px] xl:h-[327px] 2xl:w-[624px] 2xl:h-[351px]" @mouseenter="flip('rightDown')" @mouseleave="unflip('rightDown')">
          <div class="flip-card-inner relative w-full h-full" :class="{ 'flipped': flipStates.rightDown }">
            <div class="flip-card-front absolute inset-0">
              <img src="/images/GallerySectionOne/GallerySection1_5.png" alt="GallerySection1_5" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
            <div class="flip-card-back absolute inset-0">
              <img src="/images/GallerySectionTwo/GallerySection2_5.png" alt="GallerySection2_5" class="2xl:w-[624px] 2xl:h-[351px]"/>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- ОТЗЫВЫ -->
  <div class="min-h-screen flex flex-col justify-center items-center gap-15 px-10">
    <h5 class="text-white font-Caprasimo text-center sm:text-[55px] md:text-[45px] lg:text-[55px] xl:text-[60px] 2xl:text-[70px]">
      Отзывы наших игроков
    </h5>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
      <div class="flex flex-col items-center">
        <div class="w-50 h-50 rounded-full overflow-hidden">
          <img src="/images/FirstPhotoReviewBlock.png" alt="SecondPhotoReviewBlock">
        </div>
        <span class="text-white font-ABeeZee text-center 2xl:text-[20px] py-[10px]">
          <span class="font-capture-it">Rizzy</span>
           <br/> rizzy5110
        </span>
        <span class="text-white font-ABeeZee text-center 2xl:text-[20px]">
          <br/>Классный сервер с достаточно понятными механиками отзывчивой и доброй администрацией, если хочется пвпшить с тобой будут пвпшить но и закрутить рп в честное пвп тоже можно. В общем то все класс супер
        </span>
      </div>
      <div class="flex flex-col items-center">
        <div class="w-50 h-50 rounded-full overflow-hidden">
          <img src="/images/SecondPhotoReviewBlock.png" alt="SecondPhotoReviewBlock">
        </div>
        <span class="text-white font-ABeeZee text-center 2xl:text-[20px] py-[10px]">
          <span class="font-capture-it">V1xey</span>
           <br/> v1xey
        </span>
        <span class="text-white font-ABeeZee text-center 2xl:text-[20px]">
          <br/>Вполне приятный сервер, как и администрация. Достаточно заполненная карта. Различные тайники, подземелья и т.д.
        </span>
      </div>
      <div class="flex flex-col items-center">
        <div class="w-50 h-50 rounded-full overflow-hidden">
          <img src="/images/ThirdPhotoReviewBlock.png" alt="SecondPhotoReviewBlock">
        </div>
        <span class="text-white font-ABeeZee text-center 2xl:text-[20px] py-[10px]">
          <span class="font-capture-it">Last1k</span>
           <br/> Last1k_TTV
        </span>
        <span class="text-white font-ABeeZee text-center 2xl:text-[20px]">
          <br/>Выживание здесь как в ЧЗО! здесь нету ультрасупер зараженных типов аля ОД деревбаса здесь все атмосферно от кордона и до северной части юга!
        </span>
      </div>
    </div>

    <p class="text-white font-Caprasimo text-center sm:text-[30px] md:text-[25px] lg:text-[30px] xl:text-[35px] 2xl:text-[40px]">
      Больше реальных отзывов <br/> смотри в нашем Discord-сервере
    </p>
      <ButtonReviews/>
  </div>
  <!-- FOOTER -->
  <div class="sm:p-10">
    <div class="flex flex-col items-center gap-15 ">
      <p class="text-white font-Caprasimo text-center sm:text-[30px] md:text-[35px] lg:text-[45px] xl:text-[60px] 2xl:text-[80px] leading-none ">
        Вы можете помочь нашему серверу через<br/> наш магазин или Boosty:
      </p>
      <hr class="h-2 bg-[#966EA2] border-0 sm:w-130 md:w-150 lg:w-200 xl:w-280 2xl:w-400">
      <ButtonStoreFooter />
      <div id="support-section" class="flex flex-row items-center">
        <a href="https://www.tiktok.com/@last_zone_stalker?_t=ZM-8tpPuNHz9kd&_r=1" target="_blank" rel="noopener noreferrer">
          <img src="/images/icons/TikTokLogo.png" alt="logo" class="sm:w-[100px] md:w-[120px] lg:w-[140px] xl:w-[160px] 2xl:w-[175px]">
        </a>
        <a href="https://vk.com/lastzonerp" target="_blank" rel="noopener noreferrer">
          <img src="/images/icons/VkLogo.png" alt="logo" class="sm:w-[100px] md:w-[120px] lg:w-[140px] xl:w-[160px] 2xl:w-[175px]">
        </a>
        <a href="https://lastzonerp.ru/" target="_blank" rel="noopener noreferrer">
          <img src="/images/icons/DonatShopLogo.png" alt="logo" class="sm:w-[100px] md:w-[120px] lg:w-[140px] xl:w-[160px] 2xl:w-[175px]">
        </a>
        <a href="https://youtube.com/@lastzone-s2v?si=mB2MhNNpoVarwmFo" target="_blank" rel="noopener noreferrer">
          <img src="/images/icons/YoutubeLogo.png" alt="logo" class="sm:w-[100px] md:w-[120px] lg:w-[140px] xl:w-[160px] 2xl:w-[175px]">
        </a>
        <a href="https://discord.gg/last-zone" target="_blank" rel="noopener noreferrer">
          <img src="/images/icons/DiscordLogo.png" alt="logo" class="sm:w-[100px] md:w-[120px] lg:w-[140px] xl:w-[160px] 2xl:w-[175px]">
        </a>
      </div>
      <p class="text-[#966EA2] font-capture-it text-center sm:text-[10px] md:text-[13px] lg:text-[15px] xl:text-[17px] 2xl:text-[20px]">
        Все пожертвования добровольны и не ломают баланс игры, позволяя нам использовать наилучшие мощности для размещения сервера
      </p>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
import ButtonBlockServerDS from '@/components/ui/ButtonBlockServerDS.vue'
import ButtonBlockServerOther from '@/components/ui/ButtonBlockServerOther.vue'
import ButtonGoOne from '@/components/ui/ButtonGoOne.vue'
import ButtonGoTwo from '@/components/ui/ButtonGoTwo.vue'
import ButtonGoThree from '@/components/ui/ButtonGoThree.vue'
import ButtonReviews from '@/components/ui/ButtonReviews.vue'
import ButtonStoreFooter from '@/components/ui/ButtonStoreFooter .vue'

// Все состояния
const flipStates = ref<Record<string, boolean>>({
  center: false,
  leftTop: false,
  leftDown: false,
  rightTop: false,
  rightDown: false
})

// Универсальная функция для переворота
const flip = (card: string) => {
  flipStates.value[card] = true
}

const unflip = (card: string) => {
  flipStates.value[card] = false
}
</script>

<style scoped>
.flip-card {
  perspective: 1000px; /*расстояние от глаз глаз зрителя(делает анимацию более сдеражанной)*/
}

.flip-card-inner {
  transform-style: preserve-3d; /* Объявляем что элементы не 2д а 3д */
  transition: transform 1s; /* анимация переворота */
}

/* Поворачивает внутренний контейнер на 180 градусов по оси Y */
.flip-card-inner.flipped {
  transform: rotateY(180deg);
}

/* Скрывает обратную сторону элементов при повороте */
.flip-card-front,
.flip-card-back {
  backface-visibility: hidden;
}

/* Задняя сторона изначально повернута */
.flip-card-back {
  transform: rotateY(180deg);
}
</style>
