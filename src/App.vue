<template>
  <div >
    <Title/>
    <Header/>
    <Hero/>
    <Footer/>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Title,
    Header,
    Hero,
    Footer
  }
}
</script>

<style >
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: darkorange;
    text-align: center;
  }

</style>
