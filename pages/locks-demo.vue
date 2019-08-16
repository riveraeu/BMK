<template>
  <div class="container mx-auto py-20 px-6 sm:px-0">
    <h1 class="header py-2">Locks Demonstration</h1>
    <p>Click <a href="mailto:Andrea.Kraemer@cbnorcal.com,Marc.Chappell@cbnorcal.com?subject=Locks Demo Signup">here</a> to sign up for a Lock Demoonstration!</p>
    <div class="flex flex-wrap">
      <div class="w-full sm:w-1/2">
        <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1558919269/BMK/waterways-map.jpg" alt="map of BMK waterways">
        <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1565923416/BMK/BMK-locks.jpg" alt="flyer with information about locks demo">
      </div>
      <div class="w-full sm:w-1/2 p-4 items-center">
        <p class="title font-bold">Marina Lock</p>
        <i>October 1976</i>
        <a href="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1558977512/BMK/lock_history.pdf" target="_blank">
          <p class="pb-4">View PDF</p>
          <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1559096319/BMK/lock-history-cover.jpg" alt="BMK home brochure cover">
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: "BMK - Locks Demo"
    }
  }
}
</script>


<style scoped>
.container a {
  color: #066fe2;
}
.container a:hover {
  border-color: #066fe2;
}
</style>

