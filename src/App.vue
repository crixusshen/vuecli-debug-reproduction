<!--
 * @Description: In User Settings Edit
 * @Author: your name
 * @Date: 2019-09-01 10:43:42
 * @LastEditTime: 2019-09-02 11:02:47
 * @LastEditors: Please set LastEditors
 -->
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <HelloWorld2 msg="Welcome to Your React.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/A/HelloWorld.vue'
import HelloWorld2 from './components/B/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    HelloWorld2
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
