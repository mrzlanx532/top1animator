<script setup lang="ts">
import Hero from '@/components/sections/Hero.vue'
import Tariffs from '@/components/sections/Tariffs.vue'
import OpenForm from '@/components/sections/OpenForm.vue'
import Characters from '~/components/sections/Characters.vue'
import Reviews from '~/components/sections/Reviews.vue'
</script>

<template>
  <div id="page">
    <Hero />
    <Tariffs />
    <Characters />
    <Reviews />
    <OpenForm />
  </div>
</template>
