<template>
  <div class="container d-flex flex-column justify-content-center">
    <div class="spinner-border" role="status">
      <span class="visually-hidden">Loading...</span>
    </div>
    <p class="text-center">{{ text }}</p>
  </div>
</template>

<script>
export default {
  name: "Spinner",
  props: {
    text: String,
  },
};
</script>

<style></style>
