<template>
  <div>
    <Navbar />
    <div class="output container">
      <h2>{{ message }}</h2>

      <Functions />
    </div>




    <Footer msg='text message'/>
    <Footer :msg='message'/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import Functions from './components/Functions.vue'
export default {
  name: 'App',
  components: { Navbar, Footer, Functions },
  data() {
    return {
      message: 'Ett meddelande från våran data'
    }
  }

}
</script>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
.container {
  width: 80%;
  margin: auto;
}
.output{
  min-height: 300px;
}
</style>