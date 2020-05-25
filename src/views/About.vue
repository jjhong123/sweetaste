<template>
  <div class="product">
    <Header/>
    <h1>This is an product page</h1>
    <Footer/>
  </div>
</template>
<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Product",
  components: {
    Header,
    Footer
  }
};
</script>