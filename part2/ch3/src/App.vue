<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <router-view></router-view>
    <SimpleComp></SimpleComp>
    <HeaderModule></HeaderModule>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    
  </div>
</template>

<script>
import HeaderModule from './components/HeaderModule.vue'
import SimpleComp from './components/SimpleComp.vue'
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    HeaderModule,
    HelloWorld,
    SimpleComp
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
