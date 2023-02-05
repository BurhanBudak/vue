<template>
  <div>
    <navbar/>
    <div class="container">
      <example-1/>
      <example-2  class="mt"/>
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Example1 from './components/Example1.vue';
import Example2 from './components/Example2.vue';
export default {
  name: 'App',
  components: { Navbar, Example1, Example2 },

}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  width: 80%;
  margin: auto;
}
.mt{
  margin-top: 2rem;
}
.green{
  color: green; 
}
.red{
  color: red;
}
</style>