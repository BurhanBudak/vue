<template>
  <div id="app">
    <HeaderVue title="Images"/>
    <Carousel/>
    <Deck/>
  </div>
</template>

<script>
import Carousel from './components/Carousel.vue'
import Header from './components/Header.vue'
import Deck from './components/cards/Deck.vue'
export default {
  name: 'App',
  components: {
    HeaderVue: Header,
    Carousel,
    Deck
  },
}
</script>

<style>

</style>
