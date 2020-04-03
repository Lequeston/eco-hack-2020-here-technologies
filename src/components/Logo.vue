<template lang="pug">
  .logo
    img(src="@/assets/logo.png" alt="image")
    .text {{titleText}}
</template>

<script>
  export default {
    name: "Logo",
    data(){
      return{
        imgLink: "@/assets/logo.png",
        titleText: "CYCLECOIN",
      }
    }
  }
</script>

<style lang="sass" scoped>
  .logo
    display: flex
    flex-direction: row
    align-items: center
    width: 100px
    height: 100%
    padding: 20px 0 20px 0

    img
      height: 100%
      width: 40px
      display: block
      margin: auto

    .text
      font-size: 15px
      font-family: Roboto Slab
      font-style: normal
      font-weight: normal
      line-height: 20px
      display: flex
      align-items: center
      text-align: center
</style>