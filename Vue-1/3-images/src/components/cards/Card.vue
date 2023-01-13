<template>
    <div class="col">
        <div class="card" style="width: 18rem;">
            <img :src="imgURL" class="card-img-top" alt="..."/>
            <div class="card-body">
                <h5 class="card-title">{{ title }}</h5>
                <p class="card-text">{{ text }}</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Card',
    props: ['title', 'text', 'imgURL']
    // props: {
    //     title: {
    //         type: String,
    //         required: false,
    //         default: 'En rubrik'
    //     },
    //     text: {
    //         type: String,
    //         required: false,
    //         default: 'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cum temporibus dolorum earum et molestiae officiis eligendi vero pariatur laborum reprehenderit? Nam minus, voluptates veritatis explicabo harum maxime consequatur quidem omnis.'
    //     },
    //     imgURL: {
    //         type: String,
    //         required: false,
    //         default: 'https://mdbcdn.b-cdn.net/img/new/standard/nature/184.webp'
    //     }
    // }
}
</script>

<style>

</style>