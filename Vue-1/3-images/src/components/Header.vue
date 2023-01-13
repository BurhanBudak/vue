<template>
        <header class="p-2 text-start bg-info">
            <h1 class="mb-3" title="">{{ title }}</h1>
        </header>
</template>

<script>
export default {
    name: 'Header',
    props: {
        title: {
            type: String,
            required: true,
            default: 'En title'
        }
    }
  
}
</script>

<style>

</style>