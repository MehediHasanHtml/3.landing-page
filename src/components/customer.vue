<template>
    <section class="customer">
        <div class="container">
            <div class="row">
                <div class="col-lg-4">
                    <div class="title">
                        <h4>TESTIMONIALS</h4>
                        <h2>Our Customers Feedbck</h2>
                    </div>
                </div>
                <div class="col-lg-8">
                    <Carousel :autoplay="5000" :wrap-around="true" :settings="settings">
                        <Slide v-for="slider in 10" :key="slider.id">
                        <div class="carousel__item">
                            <p>{{ slider.pera }}</p>
                            <img :src="slider.img" alt="">
                        </div>
                        </Slide>
                    </Carousel>
                </div>
            </div>
        </div>
    </section>
</template>



<script setup>
import { ref } from 'vue';
import { Carousel, Slide } from 'vue3-carousel'
import 'vue3-carousel/dist/carousel.css'

const slider = ref([
    {
        id: 1,
        img: '../assets/img/person_2.jpg.webp',
        pera: 'Separated they live in Bookmarksgrove right at the coast of the Semantics , a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia.'
    },
    {
        id: 2,
        img: '../assets/img/person_2.jpg.webp',
        pera: 'Separated they live in Bookmarksgrove right at the coast of the Semantics , a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia.'
    },
    {
        id: 3,
        img: '../assets/img/person_2.jpg.webp',
        pera: 'Separated they live in Bookmarksgrove right at the coast of the Semantics , a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia.'
    },
]);


const settings = {
    // carousel settings
    settings: {
      itemsToShow: 3,
      snapAlign: 'center',
    }

};


</script>


<style>

.carousel__item {
  min-height: 200px;
  width: 100%;
  background-color: var(--vc-clr-primary);
  color: var(--vc-clr-white);
  font-size: 20px;
  border-radius: 8px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.carousel__slide {
  padding: 10px;
}

.carousel__prev,
.carousel__next {
  box-sizing: content-box;
  border: 5px solid white;
}
</style>