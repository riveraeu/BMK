<template>
  <div class="container mx-auto py-20 px-6 sm:px-0 local-experts">
    <h1 class="py-4 header">Home Sales & Listings</h1>
    <div class="pdf  mb-4">
      <a href="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1569984659/BMK/MR_pdf.pdf" target="_blank">View PDF</a>
    </div>
    <a v-for="(page, index) in marketReport" :key="index"
     href="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1569984659/BMK/MR_pdf.pdf" target="_blank">
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
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1567649805/BMK/MR_2.jpg', 'alt': 'BMK Market Report Page 2' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1567649805/BMK/MR_3.jpg', 'alt': 'BMK Market Report Page 3' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1567649806/BMK/MR_4.jpg', 'alt': 'BMK Market Report Page 4' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1567649805/BMK/MR_5.jpg', 'alt': 'BMK Market Report Page 5' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1567649805/BMK/MR_6.jpg', 'alt': 'BMK Market Report Page 6' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1567649805/BMK/MR_7.jpg', 'alt': 'BMK Market Report Page 7' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1569984656/BMK/MR_8.jpg', 'alt': 'BMK Market Report Page 8' }
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