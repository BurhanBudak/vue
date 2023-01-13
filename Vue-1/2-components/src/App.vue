<template>
  <div>
    <appNavbar/>
    <Hero/>
    <testimonials/>
  </div>
</template>

<script>
import Navbar from './components/navigation/Navbar.vue';
import  Hero  from "./components/Hero/Hero.vue";
import Testimonials from './components/Testimonials/Testimonials.vue';
export default {
  name: 'App',
  components: {
    appNavbar: Navbar,
    Hero,
    Testimonials
  }
}
</script>

<style>

</style>