<template>
  <div id="app" class="container-fluid">
    <div id="nav" class="navbar">
      <div class="route-left">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
      </div>
      <div class="route-center">
        <router-link to="/landie">Landie</router-link>
      </div>
      <b-button class="route-right" squared variant="warning">Button Label</b-button>
    </div>
    <router-view/>
  </div>
</template>
<style lang="stylus">
#app
  width 1310px
  min-height 1161px
  background-image url('assets/img1.png')
  background-position top right
  background-repeat no-repeat
  background-size contain
  .container-fluid
    font-family 'Avenir', Helvetica, Arial, sans-serif
#nav
  .route-center
    position absolute
    right 58%
    left 42%
    a
      font-size 1.5rem
      font-weight bold
      color #364386
  .route-right
    width 160px
    height 26px
    margin-right 140px
    font-size 13px
  a
    color #4e5e96
    font-family sans-serif
    font-size 13px
    font-weight 400
    light-height 30px
    text-decoration none
    padding-right 66px
    &.router-link-exact-active
      color #364386
</style>
