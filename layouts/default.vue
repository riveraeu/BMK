<template>
  <div>
    <Navbar />
    <nuxt />
  </div>
</template>

<script>
import Navbar from '~/components/navbar'

export default {
  components: {
    Navbar
  }
}
</script>

<style>
/* Elements and Layout */
html {
  font-family: Roboto;
  font-size: 14px;
  color: #16202A;
  letter-spacing: .5px;
  box-sizing: border-box;
}
img {
  width: 100%;
}
a {
  text-decoration: none;
  transition: all ease-in .4s;
  border-bottom: 1px solid transparent;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

/* Classes  */
.header {
  font-size: 18px;
  font-weight: bold;
}
.title {
  font-size: 15px;
}

/* Media Queries */

@screen xl {
  html {
    font-size: 20px;
  }
  .header {
    font-size: 24px;
  }
  .title {
    font-size: 21px;
  }
}
/* @screen xxl {
  html {
    font-size: 24px;
  }
  .header {
    font-size: 28px;
  }
  .title {
    font-size: 25px;
  }
} */
</style>
