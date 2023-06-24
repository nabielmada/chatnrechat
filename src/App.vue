<script>
import Navbar from "./components/Navbar.vue"
import Intro from "./components/Intro.vue"

export default {
  name: "App",
  components: {
    Navbar,
    Intro
  },
}
</script>

<template>
  <div>
    <Navbar />
    <Intro />
  </div>
</template>

<style scoped>

</style>
