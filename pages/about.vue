<template>
  <div class="container mx-auto py-20 px-6 sm:px-0">
    <h1 class="py-4 header">About Marc and Andrea</h1>
    <contactInfo />
    <p class="mt-8">With 26 years of Real Estate experience, <b>Andrea</b> has extensive knowledge of trends and intricacies of
    Real Estate making her the perfect guide when you want to buy or sell a property. Her previous
    experiences and community knowledge uniquely qualifies her to assist in the search for an exceptional
    property for buyers, and secures the perfect buyer for sellers. Andrea’s philosophy of putting her clients
    first shows in her day to day kindness and passion of helping people. Andrea becomes not just your
    Real Estate agent but your advocate in a transaction where its finding the perfect buyer for your present
    home or locating the perfect home for you, Andrea is ready.</p>
    <p class="mb-8">During Andrea’s free time it wouldn’t be unusual to see her walking local Novato trails with her 2 dogs
    Sammy and Haley or boating in the SF bay with her husband Stefan and son Adam. Her love of the
    outdoors and with her family is what makes her the perfect guide for your adventures.</p>
    <p class="mt-8"><b>Marc</b> has a passion for real estate, works seven days a week and always puts his client’s needs
    first. He truly enjoys it all, from helping a first time homebuyer, to assisting a family selling their
    home, working with investors and assisting a company buy or sell a commercial building are all
    within in his skill set.</p>
    <p>Marc has a very strong business background that includes owning half of a securities company,
    a mining company, acting as an accountant, owning an online fine art business and flipping
    properties. He flipped his first property over thirty years ago and was at one time a buyer’s
    agent for a large home flipping company.</p>
    <p>Marc is very well educated and believes in constantly raising his personal bar. He holds a
    Bachelor’s Degree in Business Management, a Master’s Degree in Business Administration
    (MBA) with a concentration in e-Business. Marc recently obtained a real estate Broker’s
    License.</p>
    <p class="mb-8">Being of service is his highest calling!</p>
  </div>
</template>

<script>
import contactInfo from '~/components/contact-info'

export default {
  components: {
    contactInfo
  }  
}
</script>

<style scoped>
p {
  @apply py-2
}
</style>

