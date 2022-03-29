<template>
  <div id="app">
    <Header/>
    <Hero/>
    <Content/>
    <Bonus/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Bonus from './components/Bonus.vue'
import Footer from './components/Footer.vue'
import Hero from './components/Hero.vue'





export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Content,
    Bonus,
    Footer,
  }
}
</script>

<style lang="scss">
*{  
  margin: 0;
  box-sizing: border-box;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  
}
</style>
