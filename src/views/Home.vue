<template lang="pug">
  .home
    Header
    MainHome
    Footer
</template>

<script>

import Header from "@/components/Header";
import MainHome from "@/components/MainHome";
import Footer from "@/components/Footer";

export default {
  name: 'Home',
  components: {
    Footer,
    MainHome,
    Header
  }
}
</script>

<style lang="sass" scoped>
  .home
    width: 100%
    height: auto
</style>
