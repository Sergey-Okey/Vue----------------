<script>
import Header from '../src/components/Header.vue';
import Footer from '../src/components/Footer.vue';
import Home from '../src/components/Home.vue';

export default {
  components: {
    Header,
		Home,
    Footer,
  },
};
</script>

<template>
  <div id="app">
    <Header />
    <router-view />
    <Footer />
  </div>
</template>
