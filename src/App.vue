<template>
<Navbar/>
  <Home/>
  <About/>
  <Journey/>
  <Skills/>
  <Projects/>
  <Contact/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Journey from './components/Journey.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'
import Contact from './components/contact.vue'

export default {
  name: 'App',
  components: {
   Navbar, Home,About,Journey,Skills,Projects,Contact
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
</style>
