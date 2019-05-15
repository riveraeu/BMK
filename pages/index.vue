<template>
  <div id="root">
    <section class="hero relative">
      <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1557606140/BMK/heroImage.jpg" alt="View of Bel Marin Keys water with a boat, island, and houses in the background">
      <div class="overlay text-white absolute text-center">
        <p class="header">
          BelMarinKeys.Info
        </p>
        <p class="title">
          One Stop for BMK Real Estate and<br>Community Info
        </p>
        <a class="pt-4 no-underline text-white inline-block" href="/homeSales">Explore Homes</a>
      </div>
    </section>
    <section class="container mx-auto py-20 px-6 sm:px-0 local-experts">
      <div class="flex flex-wrap">
        <div class="w-4/5 sm:w-2/5">
          <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1557875262/BMK/MarcandAndrea-CBHeadshot.jpg" alt="Headshot of Marc and Andrea">
        </div>
        <div class="sm:pl-8 flex flex-col flex-wrap">
          <div class="pb-4">
            <p>Andrea Kraemer</p>
            <p>REALTOR®</p>
            <p>CalRE #02002761</p>
            <a href="tel:415.408.1091">415.408.1091</a><br>
            <a href="mailto:Andrea.Kraemer@cbnorcal.com">Andrea.Kraemer@cbnorcal.com</a><br>
            <a href="https://www.andreasellsmarin.com/">AndreaSellsMarin.com</a>
          </div>
          <div>
            <p>Marc Chappell</p>
            <p>MBA, Broker Associate</p>
            <p>CalRE #01864642</p>
            <a href="tel:415.328.2992">415.328.2992</a><br>
            <a href="Marc.Chappell@cbnorcal.com">Marc.Chappell@cbnorcal.com</a><br>
            <a href="https://www.GreatHomesMarin.com">GreatHomesMarin.com</a>
          </div>
        </div>
      </div>
      <div class="pt-6">
        <p class="header pb-2">Local Experts</p>
        <p>
          With 26 years of Real Estate experience, Andrea has extensive knowledge of trends and intricacies of Real Estate making her the perfect guide when you want to buy or sell a property.
          Marc has a passion for real estate, works seven days a week and always puts his client’s needs first. Get in contact today with these Bel Marin Keys real estate experts.
        </p>
        <a class="font-bold pt-2 inline-block" href="/contact">Contact</a>
      </div>
    </section>
    <section class="background-light-grey">
      <p class="container mx-auto py-16 px-6 sm:px-0">
        Bel Marin Keys is an beautiful waterfront community located east of the city of Novato.
        The community has approximately 700 homes. Most of the homes sit either on one of the many lagoons or on Novato Creek.
        All of the lagoons have access to San Pablo Bay through the navigational locks. Bel Marin Keys was a planned community built between the late 1950s and late 1980s.
        Phases 1 through 4 were completed, but phase 5 was never built and instead the land is in the process of being restored back into the wetlands of Whiteside marsh, which were drained in the early 1900s for farm land.
      </p>
    </section>
    <section class="community-history container mx-auto py-20 px-6 sm:px-0">
      <div class="flex flex-wrap">
        <div class="w-1/2 sm:w-1/4">
          <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1557875261/BMK/kidsPlaying.jpg" alt="Kids playing on green field">
        </div>
        <div class="sm:pl-8 w-3/4">
          <p>Bel Marin Keys has great community events for you and your family. Get the information you need about all upcoming events and important community contacts.</p>
          <a class="font-bold pt-2 inline-block" href="/community">Community Info</a>
        </div>
      </div>
      <div class="flex flex-wrap pt-12">
        <div class="sm:pr-8 w-3/4 sm:text-right order-2">
          <p>Bel Marin Keys has a great history that is really unique and interesting. Read about the founding of this community and the history behind its development. Really good stuff here.</p>
          <a class="font-bold pt-2 inline-block" href="/history">Historical Info</a>
        </div>
        <div class="w-1/2 sm:w-1/4">
          <img src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1557875261/BMK/historicalImage.jpg" alt="Old black and white photograph of Bel Marin Keys">
        </div>
      </div>
    </section>
    <section class="background-light-grey">
      <div class="container mx-auto py-16 px-6 sm:px-0">
        <p class="header pb-2">Great Place to Live</p>
        <div class="flex flex-wrap items-center">
          <p class="sm:w-3/5">Sounds like a great place to live right? Now is a great time to look for your dream home, take a look at recent home sales and current listing. When you need help, Marc and Andrea are the local experts to help you find your new home in Bel Marin Keys.</p>
          <a class="font-bold pt-4 sm:pt-0 mx-6 " href="/contact">Get in Touch</a>
          <a class="font-bold pt-4 sm:pt-0 mx-6" href="/homeSales">Home Sales & Listings</a>
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
.order-2 {
  order: 2;
}
.overlay {
  bottom: 10%;
  right: 15%;
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
