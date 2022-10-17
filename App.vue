<template>
  <SlideCard />
</template>

<script>
import SlideCard from "./components/SlideCard.vue";

export default {
  name: "App",
  components: {
    SlideCard,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Work+Sans:wght@100;400&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,800;1,800&family=Work+Sans:wght@100;400&display=swap");
#app {
  font-family: Work Sans, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 100%;
}
</style>
