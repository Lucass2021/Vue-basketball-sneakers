<template>
    <div>
      <q-carousel
        swipeable
        animated
        v-model="slide"
        thumbnails
        infinite
        :autoplay="autoplay"
        @mouseenter="autoplay = false"
        @mouseleave="autoplay = true"
      >
        <q-carousel-slide class="banner-img" :name="1" img-src="../assets/banners/michael-jordan.jpg">
          <div class="overlay"></div>
          <div class="banner-text-container">
            <h1>Jordan's Court Dominance</h1>
            <p>Step into greatness with the iconic Jordan sneakers, a timeless collaboration between Nike and basketball legend Michael Jordan.</p>
          </div>
        </q-carousel-slide>
  
        <q-carousel-slide class="banner-img" :name="2" img-src="../assets/banners/lebron-james.jpg">
          <div class="overlay"></div>
          <div class="banner-text-container">
            <h1>LeBron's Signature Stride"</h1>
            <p>Experience the power and precision of LeBron James through his exclusive line of basketball shoes. Elevate your game with the LeBron signature series.</p>
          </div>
        </q-carousel-slide>
  
        <q-carousel-slide class="banner-img" :name="3" img-src="../assets/banners/kobe-bryant.jpg">
          <div class="overlay"></div>
          <div class="banner-text-container">
            <h1>Kobe's Legacy on Your Feet"</h1>
            <p>Walk in the footsteps of greatness with the Kobe Bryant collection. Explore the legacy of a basketball icon through his signature line of shoes. Lace up, and embrace the Mamba mentality.</p>
          </div>
        </q-carousel-slide>
      </q-carousel>
    </div>
</template>
  
<script setup>
  import { ref } from 'vue'
  
  const slide = ref(1)
  const autoplay = ref(true)

</script>
  
<style scoped>
  .banner-img {
    background-position: top;
    position: relative;
  }
  
  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5); 
  }
  
  .banner-text-container {
    position: relative; 
    padding: 50px;
    color: #fff;
    text-align: center;
  }

  .banner-text-container h1{
    font-size: 40px;
  }

  .banner-text-container p{
    font-size: 14px;
    max-width: 500px;
    margin:0 auto;
  }
</style>

<!-- Pick a font
Fix banner in mobile -->
  

