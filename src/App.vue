<script setup>
  import Navbar from "./components/Navbar.vue"
  import About from'./components/About.vue'
  import Projects from "./components/Projects.vue"
  import Tools from "./components/Tools.vue"
  import Contact from './components/Contact.vue'
  import FooterComponent from './components/Footer.vue'
</script>

<template>
  <Navbar />

  <div className = "container-fluid">
    <About />
    <Projects />
    <Tools />
    <Contact />
  </div>

  <FooterComponent />
</template>
