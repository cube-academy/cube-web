<template>
  <div id="app">
    <v-tabs right>
      <v-tab>
        <router-link to="/">Home</router-link>
      </v-tab>
      <v-tab>
        <router-link to="/about">About</router-link>
      </v-tab>
      <v-tab>
        <router-link to="/forum">Forum</router-link>
      </v-tab>
      <v-tab>
        <router-link to="/learning-plan">Learning Plan</router-link>
      </v-tab>
    </v-tabs>
    <router-view/>
  </div>
</template>

<script>

export default {
  data() {
    return {
      activeIndex: 1
    };
  }
};
</script>

<style lang="sass">
#app
  font-family: 'Avenir', Helvetica, Arial, sans-serif
  -webkit-font-smoothing: antialiased
  -moz-osx-font-smoothing: grayscale
  text-align: center
  color: #2c3e50

.v-tabs__wrapper
  background: #333
  a
    text-decoration: none
    color: #fefefe
</style>
