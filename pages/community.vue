<template>
  <div class="container mx-auto py-20 px-6 sm:px-0">
    <h1 class="header py-4">Community Info</h1>
    <div class="flex flex-wrap">
      <div class="w-3/4 sm:w-1/2 sm:pr-10">
        <img class="pb-4" src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1558892606/BMK/4th.jpg" alt="People celebrating 4th of july in boat covered in American flags">
        <div class="pb-4">
          <h2 class="title py-2">Emergency Contacts:</h2>
          <table>
            <tr>
              <td>BMK Community Center Office</td>
              <td><a href="tel:415.883.4222">415.883.4222</a></td>
            </tr>
            <tr>
              <td>BMK Waterways Manager</td>
              <td><a href="tel:415.637.7282">415.637.7282</a></td>
            </tr>
            <tr>
              <td>Novato Fire District</td>
              <td><a href="tel:415.878.2690">415.878.2690</a></td>
            </tr>
            <tr>
              <td>Marin County Sheriff</td>
              <td><a href="tel:415.479.2311">415.479.2311</a></td>
            </tr>
            <tr>
              <td>CA Fish and Wildlife</td>
              <td><a href="tel:707.944.5588">707.944.5588</a></td>
            </tr>
            <tr>
              <td>Vessel Assist/TowBoat SF</td>
              <td><a href="tel:1.877.422.9869">1.877.422.9869</a></td>
            </tr>
            <tr>
              <td>Marin Humane Society</td>
              <td><a href="tel:415.883.4621">415.883.4621</a></td>
            </tr>
            <tr>
              <td>WildCare Solutions</td>
              <td><a href="tel:415.456.7283">415.456.7283</a></td>
            </tr>
          </table>
        </div>
        <div class="pb-10">
          <h2 class="title py-2">Community Events:</h2>
          <table>
            <tr>
              <td>07/04/19</td>
              <td>4th of July Sailabration</td>
            </tr>
            <tr>
              <td>09/14/19</td>
              <td>Paddlefest</td>
            </tr>
            <tr>
              <td>10/19/19</td>
              <td>Halloween Crafts & Pumpkin Carving</td>
            </tr>
            <tr>
              <td>12/14/19</td>
              <td>Santa By Sea</td>
            </tr>
          </table>
        </div>
      </div>
      <div class="w-3/4 sm:w-1/2 sm:pl-10">
        <img class="pb-4" src="https://res.cloudinary.com/rivera-web-solutions/image/upload/v1565745590/BMK/Tennis_Racket_and_Balls.jpg" alt="Tennis racket and balls">
        <p class="font-bold pt-2 inline-block" href="/community">TENNIS ANYONE?</p>
        <p>Our new tennis courts are being under-utilized. The tennis courts are brand new.
        We are reaching out to our ladies who want to play!  A list of “Tennis Players” is being complied for all interested players in our community. Let’s play…Please call Mathilde White at <a href="tel:415 250-7100">415 250-7100</a> to sign up.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: "BMK - Community"
    }
  }
}
</script>


<style scoped>
td {
  @apply pr-4
}
.container a {
  color: #066fe2;
}
.container a:hover {
  border-color: #066fe2;
}
</style>


