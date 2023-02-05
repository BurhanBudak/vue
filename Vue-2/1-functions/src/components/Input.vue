<template>
  <div>
    <label for="vueModal">data binding for vue</label>
    <input id="vueModal" type="text" v-model="text">
    <p>{{ text }}</p>
  </div>
</template>

<script>
export default {
    name: 'Input',
    data() {
        return {text: ''}
    }

}
</script>

<style>

</style>