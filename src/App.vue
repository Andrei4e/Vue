<template>
  <div id="app">
    <!-- <HomePage /> -->
    <!-- <BlogPage /> -->
    <BlogDetailsPage />
  </div>
</template>

<script>
// import HomePage from "./components/HomePage.vue";
//import BlogPage from "./components/BlogPage.vue";
import BlogDetailsPage from "./components/BlogDetailsPage.vue";

export default {
  name: "App",
  components: {
    // HomePage,
    //BlogPage,
    BlogDetailsPage
  },
};
</script>

<style>
/* #app {
  font-family: 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
