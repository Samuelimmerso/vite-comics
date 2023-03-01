<script>
import Header from "./components/Header.vue"
import ProductList from "./components/ProductList.vue"
import Footer from "./components/Footer.vue"

export default {
  data() {
    return {
      title: "Hello world"
    }
  },

  components: {Header, ProductList, Footer},
};
</script>

<template>
  <Header />
  <!-- <ProductList />
  <Footer /> -->
</template>

<style lang="scss" scoped>
</style>