<template>
  <div>
    <button>Add</button>
    <button>Subtract</button>

    <h4>Sum: {{ sum }}</h4>
  </div>
</template>

<script>
export default {
    name: 'Functions',
    data() {
        return {
            sum: 10
        }
    }
}
</script>

<style scoped>
    button{
        background-color: darkslateblue;
        padding: .3rem .8rem;
        color: #fff;
        border: none;
        margin: 1rem 1rem 1rem 0;
        cursor: pointer;
    }
</style>