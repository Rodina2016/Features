<template>
  <div class="slider xl-20 xs-22">
    <div class="slider-block">
      <VueSlickCarousel v-bind="settings">>
        <div class="slider-block__item" v-for="items in items">
          <div class="slider-block__wrap">
            <div class="slider-block__item-heading">
              {{items.title}}
            </div>
            <div class="slider-block__item-text">
              {{items.text}}
            </div>
            <a href="#" class="slider-block__item-link">
              Learn more
              <svg class="slider-block__item-icon">
                <use xlink:href="#arrow-right"></use>
              </svg>
            </a>
            <div class="slider-block__item-number">
              {{items.id}}
            </div>
          </div>
        </div>
      </VueSlickCarousel>
    </div>
  </div>
</template>

<script>
    import VueSlickCarousel from 'vue-slick-carousel'
    import 'vue-slick-carousel/dist/vue-slick-carousel.css'
    import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

    export default {
        name: 'slider',
        data() {
            return {
                items: [
                    {
                        id: 1,
                        title: 'First Feature',
                        text: 'Little Red Cap opened her eyes and when she saw the sunbeams dancing ' +
                            'to and fro through the trees and how the ground was covered with beautiful flowers.',
                    },
                    {
                        id: 2,
                        title: 'Second Feature',
                        text: 'Each time she picked one she thought that she could see an even more beautiful one a' +
                            ' little way off, and she ran after it, going further and further into the woods.',
                    },
                    {
                        id: 3,
                        title: 'Third Feature',
                        text: 'The wolf pressed the latch, and the door opened. He stepped inside, went straight to the grandmother\'s bed, and ate her up.',
                    },
                    {
                        id: 4,
                        title: 'Fourth Feature',
                        text: 'Little Red Cap had run after the flowers. After she had gathered so many that she' +
                            ' could not carry any more, she remembered her grandmother.',
                    }
                ],
                settings: {
                    "dots": true,
                    "arrows": false,
                    "rows": 2,
                    "dotsClass": "slick-dots",
                    "edgeFriction": 0.35,
                    "infinite": false,
                    "speed": 500,
                    "slidesToShow": 1,
                    "slidesToScroll": 1,
                    responsive: [
                        {
                            "breakpoint": 1280,
                            "settings": {
                                "rows": 1,
                            }
                        }
                    ]
                }
            }
        },
        components: {VueSlickCarousel},
    }
</script>
