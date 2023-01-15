<template>
  <div class="container my-5 py-5 z-depth-1">

  
  <!--Section: Content-->
  <section class="text-center px-md-5 mx-md-5 dark-grey-text">
    
    <div class="row mb-5">
      <div class="col-md-4 mx-auto">
        <div class="view mb-4 pb-2">
          <img v-on:mouseover='handleMouseOver' src="https://mdbootstrap.com/img/illustrations/undraw_connected_world_wuay.svg" class="img-fluid" alt="smaple image">
        </div>
      </div>
    </div>

    
    
    <button @click='clickFunction' type="button" class="btn btn-primary btn-rounded">{{btnText}}</button>

  </section>
  <!--Section: Content-->
</div>
</template>

<script>
export default {
    data() {
        return {
            btnText: 'Click Me'
        }
    },
    methods: {
        handleMouseOver() {
            console.log('Hover över bilden')
            this.btnText = 'hover'
        },
        clickFunction() {
            console.log('du klick på knappen')
            this.btnText = 'Click Me'
        }
    }
}
</script>

<style>

</style>