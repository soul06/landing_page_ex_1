<template>
  <div class="ld-pg-1">
    <div class="row">
      <div class="col-12 col-md-12 col-lg-6">
        <div class="content-headline">Design Your Own Pages</div>
        <div class="content-bio">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et mahnis dis parturient montes, nascetur ridiculus</div>
        <div class="content-bio">mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim.</div>
        <div class="row">
          <div class="col-12 col-md-6 col-lg-6">
            <div class="feature-panel">
              <div class="feature-img bg-blue">
                <img class="mini-logo" src="../assets/logo.png" alt="target">
              </div>
              <div class="feature-content">
                <h3>Title Goes Here</h3>
                <p>Lorem ipsum dolor sit amet, consecteteur adipis commodo ligula eget dolor</p>
                <p>Aenean massa. Cum sociis natoque penatibus e parturient montes</p>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-16 col-lg-6">
            <div class="feature-panel">
              <div class="feature-img bg-blue">
                <img class="mini-logo" src="../assets/logo.png" alt="target">
              </div>
              <div class="feature-content">
                <h3>Title Goes Here</h3>
                <p>Lorem ipsum dolor sit amet, consecteteur adipis commodo ligula eget dolor</p>
                <p>Aenean massa. Cum sociis natoque penatibus e parturient montes</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-12 col-md-12 col-lg-6">
         <img src="../assets/img2.png" alt="target">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LandingPageOne',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus">
  .ld-pg-1
    margin-top 850px
    .mini-logo
      width 20%
    .row
      .content-headline
        font-family sans-serif
        font-size 50px
        font-weight 500
        line-height 60px
        margin-bottom 25px
      .content-bio
        font-family sans-serif
        font-size 20px
        color #4e5e96
        font-weight 400
        light-height 30px
        margin-bottom 10px

</style>
