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

        <q-carousel-slide :name="1" img-src="../assets/banners/michael-jordan.jpg">
            <div class="text-container">
                <h1>Slide 1</h1>
                <h2>Texto descritivo para o Slide 1.</h2>
            </div>
        </q-carousel-slide>

        <q-carousel-slide :name="2" img-src="../assets/banners/lebron-james.jpg" />
        
        <q-carousel-slide :name="3" img-src="../assets/banners/kobe-bryant.jpg" />

      </q-carousel>
      
    </div>
  </template>

<script setup>
import { ref } from 'vue'

  const slide = ref(1)
  const autoplay = ref(true)
    

</script>

<style scoped>

</style>