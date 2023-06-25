<script>
import Navbar from "./components/Navbar.vue"
import Intro from "./components/Intro.vue"
import Footer from "./components/Footer.vue"

export default {
  name: "App",
  components: {
    Navbar,
    Intro,
    Footer
  },
}
</script>

<template>
  <div>
    <Navbar />
    <Intro />
    <Footer />
  </div>
</template>

<style scoped>

</style>
