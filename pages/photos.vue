<template>
  <div class="container mx-auto py-20 px-6 sm:px-0">
    <h1 class="header pb-6">Photos of BMK</h1>
    <div class="image-cards">
      <div v-for="(image, index) in images" :key="index" class="image-card">
        <img :src="image.src" :alt="image.alt" @click="openGallery(index)"/>
      </div>
      <LightBox ref="lightbox" :images="images" :show-light-box="false" :show-thumbs="false"/>
    </div>
  </div>
</template>

<script>
import LightBox from "~/components/lightbox/LightBox.vue"

export default {
  components: {
    LightBox,
  },
  data () {
    return {
      images: [
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/0-min.jpg', 'alt': 'View of BMK sunset over the lagoon with boats and homes in background' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/1-min.jpg', 'alt': 'View of orange sunset of BMK lagoon '},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/2-min.jpg', 'alt': 'View of BMK lagoon on clouded day, with homes and mountains in the background'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/3-min.jpg', 'alt': 'Garden on the waterfront of BMK, clouded sky and homes in the background'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/4-min.jpg', 'alt': 'Shot of BMK waterfront at twilight, purple sky with clouds'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/5-min.jpg', 'alt': 'View of BMK lagoon at sunset, orange sky reflected in the water'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/6-min.jpg', 'alt': 'View of BMK lagoon at sunset, sky refected in water'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100816/BMK/7-min.jpg', 'alt': 'Rainbow in clouded sky, over the BMK waterfront'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100816/BMK/8-min.png', 'alt': 'Shot of rainbow over BMK'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100816/BMK/9-min.jpg', 'alt': 'Double rainbow!! over BMK with water, homes, and trees in the background'},
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/10-min.jpg', 'alt': 'Another rainbow over BMK on a clouded day'}
      ]
    }
  },
  methods: {
    openGallery (index) {
      this.$refs.lightbox.showImage(index)
    },
  }
}
</script>

<style scoped>
  .image-cards {
    column-count: 3;
    column-gap: 1em;
  }
  .image-card {
    margin: 0 0 1em;
    width: 100%;
    transition: all 100ms ease-in-out;
    display: inline-block;
    cursor: pointer;
  }
  .image-card >>> img {
    width: 100%;
  }
  @media (max-width: 1264px) {
    .image-cards {
      column-count: 2;
    }
  }
  @media (max-width: 600px) {
    .image-cards {
      column-count: 1;
    }
    .image-cards {
      margin: 0 0 0;
    }
  }
  .image-cards >>> img {
    display: block;
    width: 100%;
  }
</style>