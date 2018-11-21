<template>
  <div class="home-page">
    <div class="hero-image">
      <h1>Welcome to School of Block</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
};
</script>

<style lang="sass" scoped>
.hero-image
  width: 100vw
  height: 100vh
  display: flex
  justify-content: center
  align-items: center
  text-align: center
  background-image: url(../assets/blockchain_hero.jpg)
  background-size: cover
  background-position: center center
  background-repeat: no-repeat
  background-attachment: fixed
</style>
