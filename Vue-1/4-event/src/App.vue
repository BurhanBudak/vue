<template>
  <div id="app">
    <Hero />
    <div class="container mt-5">
      <div class="row">
        <div class="col-6">
          <sign-in/>
        </div>
        <div class="col-6">
          <sign-up/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import SignIn from './components/SignIn.vue'
import SignUp from './components/SignUp.vue'


export default {
  name: 'App',
  components: {
    Hero,
    SignIn,
    SignUp,
  }
  
}
</script>

<style>

</style>
