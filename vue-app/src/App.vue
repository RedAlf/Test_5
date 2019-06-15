<template>
  <div id='app'>
    <!-- <img alt="Vue logo" src="./assets/logo.png"/> -->
    <Header user='Гость'/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Main from './components/Main'
import Header from './components/Header'
import Footer from './components/Footer'


export default {
  name: 'app',
  components: {
    Main,
    Header,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
