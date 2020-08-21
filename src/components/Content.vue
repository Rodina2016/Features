<template>
  <main id="main" class="main">
    <div class="wrapper">
      <h1 class="center-xl main__heading">
        Features
      </h1>
      <p class="center-xl main__p">
        Some of the features and advantages that we provide for those of you who store data in this Data Warehouse.
      </p>
      <app-slider></app-slider>
    </div>
  </main>
</template>

<script>
  import Slider from './Slider'
    export default {
        name: 'main',
        data () {
            return {
                msg: 'main'
            }
        },
        components: {
            AppSlider: Slider
        }
    }
</script>
