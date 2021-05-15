<template>
  <div class="art">
    <Nav />
    <h1>Projects</h1>
    <Footer />
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue"
import Footer from "@/components/Footer.vue"

export default {
  name: 'Projects',
  components: {
    Nav,
    Footer
  }
}
</script>