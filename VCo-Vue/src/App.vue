<script>
const routes = {
  '/': Home,
  '/About': About,
  '/Products': Products,
  '/Contacts': Contacts
}

export default {
  computed: {
    currentView() {
      return routes[window.location.pathname] || NotFound
    }
  },
}
</script>
<script setup>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

import Home from './views/Home.vue'
import About from './views/About.vue'
import Products from './views/Products.vue'
import Contacts from './views/Contacts.vue'
import NotFound from './views/NotFound.vue'
</script>

<template>
  <Header />
  <component :is="currentView" />
  <Footer />
</template>

<style scoped>
  
</style>