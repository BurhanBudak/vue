<template>
  <div>
    <button @click='a++'>Lägg till på A</button>
    <button @click='b++'>Lägg till på B</button>
    <br>
    <br>
    <p>Numret är {{ number }}</p>
    <p class="mt">A = {{ a }}</p>
    <p>B = {{ b }}</p>
    <br>
    <p>Number + A = {{ addToA }}</p>
    <p>Number + B = {{ addToB }}</p>
  </div>
</template>

<script>
export default {
    data() {
        return {
            number: 30,
            a: 0,
            b:0
        }
    },
    methods: {
        // addToA() {
        //     console.log('Ökade A');
        //     return this.a + this.number;
        // },
        // addToB() {
        //     console.log('Ökade B');
        //     return this.b + this.number;
        // }
    },
    computed: {
        //skillnaden är att computed returnerar en variabel jämfört med methods functioner
        addToA() {
            console.log('Ökade A');
            return this.a + this.number;
        },
        addToB() {
            console.log('Ökade B');
            return this.b + this.number;
        }
    }
}
</script>

<style>

</style>