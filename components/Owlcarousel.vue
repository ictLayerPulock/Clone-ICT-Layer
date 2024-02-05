<!-- components/OwlCarousel.vue -->

<template>
    <div class="owl-carousel owl-theme">
      <div class="item">
        <img src="image1.jpg" alt="Image 1">
      </div>
      <div class="item">
        <img src="image2.jpg" alt="Image 2">
      </div>
      <!-- Add more slides as needed -->
    </div>
  </template>
  
  <script>
  export default {
    mounted() {
      // Initialize Owl Carousel
      $('.owl-carousel').owlCarousel({
        loop: true,
        margin: 10,
        nav: true,
        autoplay: true,
        autoplayHoverPause: true,
        responsive: {
          0: {
            items: 1
          },
          600: {
            items: 3
          },
          1000: {
            items: 5
          }
        }
      });
    }
  }
  </script>
  
  <style scoped>
  /* Add custom styles if needed */
  </style>
  