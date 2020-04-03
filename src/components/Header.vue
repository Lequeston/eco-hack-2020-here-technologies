<template lang="pug">
  .header
    Logo
</template>

<script>
  import Logo from "@/components/Logo";
  export default {
    name: "Header",
    components: {Logo}
  }
</script>

<style lang="sass" scoped>
  .header
    width: 100%
    height: 80px
    display: flex
    background: gray
    padding: 0 60px 0 60px
</style>