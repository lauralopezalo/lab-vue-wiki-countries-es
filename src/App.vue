<template>
  <div className="app">
    <NavBar />
    <router-view />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";

export default {
  components: { NavBar },
  data: () => ({}),
};
</script>

<style></style>
