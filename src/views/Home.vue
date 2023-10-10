<template>
  <div>
    <Hero/>
  </div>
  <div class="services-section container mx-auto px-12 mt-24">
    <h2 class="text-[40px] text-center font-bold mb-12">What <span class="z-10 relative before:bg-secondary before:w-full before:bottom-2 before:h-3 before:absolute before:-z-10">Services</span> Do I Provide?</h2>
    <ul class="services grid grid-cols-4 gap-8 w-full">
      <li v-for="item in serviceDetails" :key="item.title" class="service">
        <Service :title="item.title" :desc="item.desc" :icon="item.icon"/>
      </li>
    </ul>
  </div>
  <div class="experience-section container mx-auto px-12 mt-24">
    <Experience/>
  </div>
</template>

<script setup>
import { reactive } from 'vue'
import Hero from '../components/Hero.vue'
import Service from '../components/Service.vue'
import Experience from '../components/Experience.vue'

const serviceDetails = reactive([
  {
    title: 'Web Development',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'fa-brands fa-instagram',
  },
  {
    title: 'App Development',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'fa-brands fa-instagram',
  },
  {
    title: 'UI Design',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'fa-brands fa-instagram',
  },
  {
    title: 'Production',
    desc: 'Varius amet, integer tellus non eget viverra. Ultrices tellus donec gravida id sed senectus dolor cursus sed.',
    icon: 'fa-brands fa-instagram',
  },
])


</script>

<style lang="scss" scoped>

</style>