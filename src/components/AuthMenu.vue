<template lang="pug">
  .auth
    router-link(to="he" class="signup") {{signUp}}
    router-link.signin(to="ne") {{signIn}}
</template>

<script>
  export default {
    name: "AuthMenu",
    data(){
      return{
        signUp: "зарегистрироваться",
        signIn: "войти"
      }
    }
  }
</script>

<style lang="sass" scoped>
  .auth
    display: flex
    flex-direction: row
    justify-content: space-between
    width: 480px
    height: 100%
    padding: 20px 0 20px 0
    box-sizing: border-box

    a
      border: 1px solid #58C800
      box-sizing: border-box
      border-radius: 20px
      font-family: 'Roboto Slab', serif
      font-style: normal
      font-weight: normal
      font-size: 15px
      line-height: 17px
      display: flex
      align-items: center
      align-content: center
      justify-content: center
      text-align: center
      height: 40px
      width: 220px
      text-decoration: none

    .signin
      background: white
      color: #58C800


    .signup
      color: #FFFFFF
      background: #58C800
</style>