<template>
  <div id="root">
    <section class="hero relative">
      <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1557606140/BMK/heroImage.jpg" alt="View of Bel Marin Keys water with a boat, island, and houses in the background">
      <div class="overlay text-white absolute text-center">
        <p class="header">
          BelMarinKeys.Info
        </p>
        <p class="title">
          One Stop for BMK
        </p>
        <div class="hero-cta pt-4">
          <a href="/community">Community</a>
          <a href="/history">History</a>
          <a href="/photos">Photos</a><br>
          <a href="/homeSales&Listings">Home Sales & Listings</a>
        </div>
      </div>
    </section>
    <section class="container mx-auto py-20 px-6 sm:px-0">
      <div class="pt-6 local-experts">
        <p class="header pb-2">Local Experts</p>
        <p>Welcome to BelMarinKeys.info! Here you will find information on the latest real estate sales and listings, photos of our community, historical photos and information.
          This site was created by Andrea Kraemer and Marc Chappell both long term residents, community enthusiasts, and local Realtors. 
          This site is a work in process and your feedback is more than welcome!
        </p>
        <a class="font-bold pt-2 inline-block" href="/about">Contact</a>
      </div>
    </section>
    <section class="background-light-grey">
      <p class="container mx-auto py-16 px-6 sm:px-0">
        Bel Marin Keys is a beautiful waterfront community located east of the city of Novato.
        The community has approximately 700 homes. Most of the homes sit either on one of the many lagoons or on Novato Creek.
        All of the lagoons have access to San Pablo Bay through the navigational locks. Bel Marin Keys was a planned community built between the late 1950s and late 1980s.
        Phases 1 through 4 were completed, but phase 5 was never built and instead the land is in the process of being restored back into the wetlands of Whiteside marsh, which were drained in the early 1900s for farmland.
      </p>
    </section>
    <section class="community-history container mx-auto py-20 px-6 sm:px-0">
      <div class="flex flex-wrap">
        <div class="w-1/2 sm:w-1/4">
          <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1558892606/BMK/4th.jpg" alt="People celebrating 4th of july in boat covered in American flag">
        </div>
        <div class="sm:pl-8 w-3/4">
          <p>Bel Marin Keys has great community events for you and your family. Get the information you need about all upcoming events and important community contacts.</p>
          <a class="font-bold pt-2 inline-block" href="/community">Community Info</a>
        </div>
      </div>
      <div class="flex flex-wrap py-16">
        <div class="sm:pr-8 w-3/4 sm:text-right order-2">
          <p>Bel Marin Keys has a great history that is really unique and interesting. Read about the founding of this community and the history behind its development. Really good stuff here.</p>
          <a class="font-bold pt-2 inline-block" href="/history">Historical Info</a>
        </div>
        <div class="w-1/2 sm:w-1/4">
          <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1557875261/BMK/historicalImage.jpg" alt="Old black and white photograph of Bel Marin Keys">
        </div>
      </div>
      <div class="flex flex-wrap">
        <div class="w-1/2 sm:w-1/4">
          <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1560100815/BMK/5-min.jpg" alt="View of BMK lagoon at sunset, orange sky reflected in the water">
        </div>
        <div class="sm:pl-8 w-3/4">
          <p>We have created a section that contains photos of our community. We welcome your photos as well, especially photos of a historical or nostalgic nature.</p>
          <a class="font-bold pt-2 inline-block" href="/photos">Photos</a>
        </div>
      </div>
    </section>
    <section class="background-light-grey">
      <div class="container mx-auto py-16 px-6 sm:px-0">
        <p class="header pb-2">Great Place to Live</p>
        <div class="flex flex-wrap items-center">
          <p>Sounds like a great place to live right? Now is a great time to look for your dream home, take a look at recent home sales and current listing. When you need help, Marc and Andrea are the local experts to help you find your new home in Bel Marin Keys.</p>
          <div class="py-4">
            <a class="font-bold mr-4" href="mailto:Andrea.Kraemer@cbnorcal.com,marc.chappell@cbnorcal.com?subject=Ask a Relator a question">Ask a Relator a question</a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>

export default {

}
</script>

<style>
.hero-cta a {
  @apply mx-4 m-2 no-underline text-white inline-block
}
.order-2 {
  order: 2;
}
.overlay {
  bottom: 10%;
  right: 25%;
}
.overlay a:hover {
  border-color: white;
}
.container a:hover {
  border-color: #16202A;
}
.background-light-grey {
  background-color: #eee;
}
.local-experts p {
  @apply py-2
}
@screen sm {
  .overlay {
    bottom: 10%;
    right: 5%;
  }
  .order-2 {
    order: 0;
  }
  .marl-25 {
    margin-left: 25%;
  }
}
</style>
