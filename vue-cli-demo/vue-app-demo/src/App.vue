<template>
  <div id="app">
    <img src="./assets/logo.png" class="py-3">
    <h1 class="py-4">{{ msg }}</h1>
    <!-- <h2>Essential Links</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul> -->

    <!-- <about-us></about-us> -->
    <profile></profile>
    <education></education>
    <skill></skill>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {
    AboutUs, Profile, Education, Skill
  },
  data () {
    return {
      msg: 'Welcome to the Vue.js App of Ethan Gonzales'
    }
  }
}

import AboutUs from './components/AboutUs.vue'
import Profile from './components/Profile.vue'
import Education from './components/Education.vue'
import Skill from './components/Skill.vue'
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
