<template>
  <div>
    <HeaderVue title="Images"/>
    <Carousel/>
    <Carddeck/>
  </div>
</template>

<script>
import Carousel from './components/Carousel.vue'
import Header from './components/Header.vue'
import Carddeck from './components/cards/CardDeck.vue'
export default {
  name: 'App',
  components: {
    HeaderVue: Header,
    Carousel,
    Carddeck
  },
  data() {
    return {
    }
  }
}
</script>

<style>

</style>
