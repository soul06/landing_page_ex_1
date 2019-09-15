<template>
  <div class="ld-pg-3">
    <img src="../assets/img6.png" alt="target">
    <div class="text-block">
      <div class="col-12 col-md-12 col-lg-6">
        <div class="content-headline">Design Your Own Pages</div>
          <div class="content-bio">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et mahnis dis parturient montes, nascetur ridiculus</div>
          <div class="action">
            <b-button class="action-btn" squared variant="outline-secondary">Button Label</b-button>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LandingPageThree'
}
</script>

<style scoped lang="stylus">
  .ld-pg-3
    position relative
    margin-top 200px
    .text-block
      position absolute
      bottom 400px
      left 400px
      color white
      padding-left 20px
      padding-right 20px
    .text-block
      .content-headline
        font-family sans-serif
        font-size 50px
        font-weight 500
        line-height 60px
        margin-bottom 25px
        color black
      .content-bio
        font-family sans-serif
        font-size 20px
        color #4e5e96
        font-weight 400
        light-height 30px
        margin-bottom 10px
</style>
