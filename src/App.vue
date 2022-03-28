<template>
  <div id="app">
    <Header/>
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




export default {
  name: 'App',
  components: {
    Header,
    Content,
    Bonus,
    Footer,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  margin: 0;
}
</style>
