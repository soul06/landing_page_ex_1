<template>
  <div class="container">
    <div class="row row-content">
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
  .container
    .row
      margin-top 50px
      .content-headline
        font-family sans-serif
        font-size 45px
        font-weight 500px
        line-height 60px
        margin-bottom 25px
      .content-bio, .content-bio2
        font-family sans-serif
        font-size 18px
        font-weight 400
        light-height 30px
        margin-bottom 10px
      .action
        .action-btn
          margin-top 30px
          margin-right 20px
</style>
