<template>
  <header class="text-white fixed z-10 w-full flex justify-between items-center">
    <div class="logo">
      <a class="title font-bold" href="/">BelMarinKeys.Info</a>
    </div>
    <div class="text-right md:hidden px-6">
      <button class="md:hidden focus:outline-none" @click="showMobileMenu = !showMobileMenu">
        <div v-for="index in 3" :key="index" />
      </button>
    </div>
    <div class="hidden md:block right-nav">
      <a href="/about">About</a>
      <a href="/contact">Contact</a>
      <a href="/community">Community</a>
      <a href="/locks-demo">Locks Demo</a>
      <a href="/history">History</a>
      <a href="">Photos</a>
      <a href="">Home Sales & Listings</a>
    </div>
    <div id="sidenav" :class="showMobileMenu ? 'w-1/2': 'w-0'" class="absolute pin-t pin-l h-screen shadow-lg overflow-x-hidden">
      <a class="title font-bold" href="/">BelMarinKeys.Info</a>
      <a href="/about">About</a>
      <a href="/contact">Contact</a>
      <a href="/community">Community</a>
      <a href="/locks-demo">Locks Demo</a>
      <a href="/history">History</a>
      <a href="">Photos</a>
      <a href="">Home Sales & Listings</a>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      showMobileMenu: false
    }
  }
}
</script>

<style>
header {
  background-color: #066fe2;
  box-shadow: inset 100vw 0 0 rgba(0,0,0,0.5);
}
header a {
  margin: 1rem;
  display: inline-block;
}
header a:hover {
  border-color: white;
}
#sidenav {
  transition: 0.5s;
  background-color: #066fe2;
  box-shadow: inset 100vw 100vh 0 rgba(0,0,0,0.5);
  @apply flex flex-col items-center
}
button div {
  width: 25px;
  height: 2px;
  background-color: white;
  margin: 5px 0;
}
.w-0 {
  width: 0;
}
</style>
