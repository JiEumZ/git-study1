<template>
  <div id="app">
    <Header></Header>
    <!-- 路由组件出口地方 -->
    <router-view></router-view>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    Header,
    Footer,
  },
};
</script>

<style>
</style>
