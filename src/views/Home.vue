<template>
  <div id="home">
    <Navbar />
    <Landing />
    <!-- <Earning /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/navbar.vue";
import Landing from '@/components/landing/index.vue'
// import Earning from '@/components/earning/index.vue'

export default {
  name: "Home",
  components: {
    Navbar,
    Landing,
    // Earning
  }
};
</script>
<style src='../sass/views/Home.sass' lang="sass" scoped>
</style>