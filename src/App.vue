<template>
  <div id="app" class="container">
    <div id="nav">
      <div class="route-left">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
      </div>
      <div class="route-center">
        <router-link to="/landie">Landie</router-link>
      </div>
      <b-button class="route-right" variant="warning">Button Label</b-button>
    </div>
    <router-view/>
  </div>
</template>
<style lang="stylus">
#app
  font-family 'Avenir', Helvetica, Arial, sans-serif
  background-image url('assets/img1.png')
  height 1000px
  background-position top right
  background-repeat no-repeat
  background-size contain
  position relative
  width 1000px
#nav
  padding-top 30px
  display flex
  justify-content space-between
  .route-center
    position absolute
    right 50%
    left 50%
  a
    color #4e5e96
    font-family sans-serif
    font-size 18px
    font-weight 400
    light-height 30px
    text-decoration none
    padding 20px
    &.router-link-exact-active
      color #0000ff
</style>
