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
    width: 200px
    height: 100%
    padding: 10px 0 10px 0
    box-sizing: border-box

    img
      object-fit: cover
      height: 60px
      width: 60px

    .text
      margin-left: 20px
      font-family: 'Playfair Display', serif
      font-style: normal
      font-weight: 300
      font-size: 25px
      line-height: 24px
      display: flex
      align-items: center
      text-align: center

      color: #58C800
</style>