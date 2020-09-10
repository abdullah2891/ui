<template>
  <v-app>
    <Navbar class="mb-3" />
    <v-content class="grey lighten-3">
      <nuxt />
    </v-content>
    <Footer />
  </v-app>
</template>

<script>
import Navbar from '~/components/base/Navbar.vue'
import Footer from '~/components/base/Footer.vue'

export default {
  components: {
    Navbar,
    Footer,
  },
}
</script>
