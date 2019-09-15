<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-12 col-md-12 col-lg-6">
        <div class="content-headline">Introduce Your Product Quickly & Effectively</div>
        <div class="content-bio">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et mahnis dis parturient montes, nascetur ridiculus</div>
        <div class="content-bio2">mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.</div>
        <div class="action">
          <b-button class="action-btn" squared variant="outline-secondary">Button Label</b-button>
          <b-button class="action-btn" squared variant="outline-secondary">Button Label</b-button>
        </div>
      </div>
      <div class="col-12 col-md-12 col-lg-6">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LandingPage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
  .container-fluid
    margin-top 300px
    .row
      .content-headline
        font-family sans-serif
        font-size 50px
        font-weight 500
        line-height 60px
        margin-bottom 25px
      .content-bio, .content-bio2
        font-family sans-serif
        font-size 20px
        color #4e5e96
        font-weight 400
        light-height 30px
        margin-bottom 10px
      .action
        .action-btn
          width 189.13px
          height 36px
          margin-top 50px
          margin-right 30px
</style>
