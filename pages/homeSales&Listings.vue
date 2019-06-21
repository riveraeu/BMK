<template>
  <div class="container mx-auto py-20 px-6 sm:px-0 local-experts">
    <h1 class="py-4 header">Home Sales & Listings</h1>
    <div class="pdf  mb-4">
      <p><i>June 10th 2019</i></p>
      <a href="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087755/BMK/url2pdf.pdf" target="_blank">View PDF</a>
    </div>
    <a v-for="(page, index) in marketReport" :key="index"
     href="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087755/BMK/url2pdf.pdf" target="_blank">
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
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0001-min.jpg', 'alt': 'BMK Market Report Page 1' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0002-min.jpg', 'alt': 'BMK Market Report Page 2' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0003-min.jpg', 'alt': 'BMK Market Report Page 3' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0004-min.jpg', 'alt': 'BMK Market Report Page 4' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0005-min.jpg', 'alt': 'BMK Market Report Page 5' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0006-min.jpg', 'alt': 'BMK Market Report Page 6' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0007-min.jpg', 'alt': 'BMK Market Report Page 7' },
        { 'src': 'https://res.cloudinary.com/rivera-web-solutions/image/upload/v1561087699/BMK/0008-min.jpg', 'alt': 'BMK Market Report Page 8' }
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