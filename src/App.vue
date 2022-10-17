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
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  margin: 0;
  min-height: 100%;
}
</style>
