<template>
  <div class="art">
    <Nav />
    <h1>Art</h1>
    <Footer />
  </div>
</template>

<script>
import Nav from "@/components/Nav.vue"
import Footer from "@/components/Footer.vue"

export default {
  name: 'Art',
  components: {
    Nav,
    Footer
  }
}
</script>