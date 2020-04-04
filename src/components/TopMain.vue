<template lang="pug">
  .top
    .blackout
    .title {{title}}
    .info {{info}}
    router-link.button(to="gg") {{buttonName}}
</template>

<script>
  export default {
    name: "TopMain",
    data(){
      return{
        title: "CYCLECOIN",
        info: "Привет, мы хотим уменьшить количество машин на дорогах. Для этого мы будем обменивать проеханное тобой расстояние на велосипеде на cyclecoin-ы. ",
        buttonName: "Ты с нами?"
      }
    }
  }
</script>

<style lang="sass" scoped>
  .top
    display: flex
    flex-direction: column
    width: 100%
    height: 945px
    background-image: url("../assets/top-backgtound.jpg")
    background-repeat: no-repeat

    .blackout
      position: absolute
      width: 100%
      height: 945px
      background: #2C2B2B
      opacity: 60%
      z-index: 1

    .title
      z-index: 2
      text-transform: uppercase
      width: auto
      height: auto
      font-family: 'Playfair Display', serif
      font-style: normal
      font-weight: bold
      font-size: 100px
      line-height: 133px
      letter-spacing: 0.02em
      color: #FFFFFF
      margin-left: 10%
      margin-top: 14%

    .info
      z-index: 2
      width: 515px
      height: 338px
      font-family: 'Roboto Slab', serif
      font-style: normal
      font-weight: normal
      font-size: 26px
      line-height: 34px
      display: flex
      align-items: center
      color: #FFFFFF
      margin-left: 10%

    a.button
      z-index: 3
      opacity: 80%
      background: #58C800
      border-radius: 40px
      margin-left: 33%
      font-family: 'Roboto Slab', serif
      font-style: normal
      font-weight: bold
      font-size: 40px
      line-height: 53px
      display: flex
      align-items: center
      text-align: center
      color: white
      text-decoration: none
      width: 500px
      height: 100px
      justify-content: center

      &:hover
        opacity: 100%


</style>