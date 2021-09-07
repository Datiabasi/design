<template>
  <div id="app">
    <Navbar />
    <Heading />
    <Content1 />
    <Content2 />
    <Content3 />
    <Content4 />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Heading from "./components/Heading.vue";
import Content1 from "./components/Content1.vue";
import Content2 from "./components/Content2.vue";
import Content3 from "./components/Content3.vue";
import Content4 from "./components/Content4.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Heading,
    Content1,
    Content2,
    Content3,
    Content4,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Jost:wght@100;200;300;400;500;600;700;800;900&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: "Jost", sans-serif;
}
</style>
