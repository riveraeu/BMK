<template>
  <div class="container mx-auto py-20 px-6 sm:px-0 local-experts">
    <h1 class="py-4 header">Home Sales & Listings</h1>
    <div class="pdf  mb-4">
      <p><i>June 10th 2019</i></p>
      <a href="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819357/BMK/MR_071019.pdf" target="_blank">View PDF</a>
    </div>
    <a v-for="(page, index) in marketReport" :key="index"
     href="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819357/BMK/MR_071019.pdf" target="_blank">
      <img :src="page.src" :alt="page.alt">
    </a>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: "BMK - Home Sales & Listings"
    }
  }, 
  data () {
    return {
      marketReport: [
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819211/BMK/MR_071019_02.jpg', 'alt': 'BMK Market Report Page 1' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819211/BMK/MR_071019_03.jpg', 'alt': 'BMK Market Report Page 2' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819211/BMK/MR_071019_04.jpg', 'alt': 'BMK Market Report Page 3' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819211/BMK/MR_071019_05.jpg', 'alt': 'BMK Market Report Page 4' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819211/BMK/MR_071019_06.jpg', 'alt': 'BMK Market Report Page 5' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1562819211/BMK/MR_071019_07.jpg', 'alt': 'BMK Market Report Page 6' }
      ]
    }
  }
}
</script>

<style scoped>
  .pdf a {
    color: #066fe2;
  }
  .pdf a:hover {
    border-color: #066fe2;
  }
</style>