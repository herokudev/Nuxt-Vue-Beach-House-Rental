<template>
    <div>
      <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="4000"
        controls
        indicators
        background="#ababab"
        img-width="256"
        img-height="120"
        style="text-shadow: 1px 1px 2px #333;"
        @sliding-start="onSlideStart"
        @sliding-end="onSlideEnd"
      >
  
        <!-- Slides with image only -->
        <b-carousel-slide img-src="https://raw.githubusercontent.com/herokudev/Nuxt-Vue-Beach-House-Rental/main/static/House07.jpg"></b-carousel-slide>
  
        <!-- Slides with image only -->
        <b-carousel-slide img-src="https://raw.githubusercontent.com/herokudev/Nuxt-Vue-Beach-House-Rental/main/static/House08.jpg"></b-carousel-slide>
  
        <!-- Slides with image only -->
        <b-carousel-slide img-src="https://raw.githubusercontent.com/herokudev/Nuxt-Vue-Beach-House-Rental/main/static/House09.jpg"></b-carousel-slide>
        
        <!-- Slides with image only -->
        <b-carousel-slide img-src="https://raw.githubusercontent.com/herokudev/Nuxt-Vue-Beach-House-Rental/main/static/House13.jpg"></b-carousel-slide>

      </b-carousel>

    </div>
  </template>
  
  <script>
    export default {
      data() {
        return {
          slide: 0,
          sliding: null
        }
      },
      methods: {
        onSlideStart(slide) {
          this.sliding = true
        },
        onSlideEnd(slide) {
          this.sliding = false
        }
      }
    }
  </script>