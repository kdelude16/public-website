<template>
  <div class="about">
    <v-layout
        text-xs-center
        wrap
        class="pt-5"
    >
      <v-flex xs12>
          <p class="title-main">
              About Us
          </p>
      </v-flex>
      <v-card class="main-card">
        <v-flex xs12 class="pt-4">
          <div class="content">

            <p>
                Movvz, Forefront of modern delivery network.
                <br/><br/>
                Moving? Don’t worry anymore! We are here to move anything to anywhere!
                <br/><br/>
                Snap a photo, post it, and someone will pick it up and deliver it for you.
                Movvz out-sources deliveries to independent drivers that’ll pick-up your item wherever you need.
                <br/><br/>
                On top of regular deliveries, our system also ensures user safety and privacy between buyers and sellers on used marketplaces like Facebook Marketplace, Craigslist, OfferUp, and LetGo.
            </p>
          </div>
          <span class="content">
            <AboutCases />
          </span>
        </v-flex>
      </v-card>
    </v-layout>
  </div>
</template>

<script>
import AboutCases from '../components/AboutCases'

export default {
  components: {
    AboutCases
  }
}
</script>

<style scoped>
.main-card{
  padding: 80px 112px
}
.content {
  text-align: left;
  padding: 0 100px;
  font-size: 18px;
}
</style>
