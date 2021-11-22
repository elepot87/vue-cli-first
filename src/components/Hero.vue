<template>
  <div class="container">
    <div class="hero-text">Un infinito di possibilità</div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-image: url("../assets/pexels-eberhard-grossgasteiger-572897.jpg");
  background-size: cover;
  height: 800px;
}

.hero-text {
  color: #fff;
  font-size: 35px;
  background-color: rgba(0, 0, 0, 0.5);
  font-style: italic;
}
</style>
