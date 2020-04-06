<template>
  <div id="app">
  <Navigation />
  <Lander />
  <Footer />
  </div>
</template>
<script>
import Navigation from '@/components/Navigation.vue'
import Lander from '@/components/Lander.vue'
import Footer from '@/components/Footer.vue'
export default {
  name: 'App',
  data () {},
  created: function () {},
  methods: {},
  components: {
  Navigation,
  Lander,
  Footer
  }
}
</script>

<style>
* {
 margin: 0;
 padding: 0;
 box-sizing:border-box;
}
</style>
