<template>
  <div >
    <Title/>
    <Header/>
    <Hero/>

  </div>
</template>

<script>
import Title from './components/Title.vue'
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'


export default {
  name: 'App',
  components: {
    Title,
    Header,
    Hero
  }
}
</script>

<style >
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  h1 {
    text-align: center;
    color: darkgreen;
  }
</style>
