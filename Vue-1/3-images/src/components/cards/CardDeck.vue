<template>
  <div class="row row cols-1 row-cols-md-3 g-4">
    <Card :imgURL='imgOne' title="HEJ" text='Detta är text'></Card>
    <Card :imgURL='imgOne' title="HEJHEJ2222" text='sjkddkldjsds'/>
    <Card imgURL="https://mdbcdn.b-cdn.net/img/new/standard/nature/184.webp"  title="bla" text='nej' />
  </div>
</template>

<script>
import Card from './Card.vue';
export default {
    name: 'CardDeck',
    components: { Card },
    data() {
        return {
            imgOne: require('@/assets/img/logo.png'),
        }
    }
}
</script>

<style>

</style>