<template>
  <div class="home">
    <LandingPage/>
    <LandingPageOne/>
    <LandingPageTwo imgName="img3" />
    <LandingPageTwo imgName="img4" />
    <LandingPageTwo imgName="img5" />
    <LandingPageThree/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import LandingPage from '@/components/LandingPage.vue'
import LandingPageOne from '@/components/LandingPageOne.vue'
import LandingPageTwo from '@/components/LandingPageTwo.vue'
import LandingPageThree from '@/components/LandingPageThree.vue'
import Footer from '@/components/Footer.vue'
export default {
  name: 'home',
  components: {
    LandingPage,
    LandingPageOne,
    LandingPageTwo,
    LandingPageThree,
    Footer
  }
}
</script>
