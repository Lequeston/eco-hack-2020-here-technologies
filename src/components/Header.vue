<template lang="pug">
  .header
    Logo
    AuthMenu
</template>

<script>
  import Logo from "@/components/Logo";
  import AuthMenu from "@/components/AuthMenu";
  export default {
    name: "Header",
    components: {AuthMenu, Logo}
  }
</script>

<style lang="sass" scoped>
  .header
    display: flex
    flex-direction: row
    justify-content: space-between
    width: 100%
    height: 80px
    background: white
    padding: 0 60px 0 60px
    box-sizing: border-box
    border-bottom: 1px solid #58C800
</style>