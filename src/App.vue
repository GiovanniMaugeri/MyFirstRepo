<template>
  <div id="app">
    <img src="./assets/logo.png">
    <MyName/>
    <HelloWorld/>
    <datetime v-model="date"></datetime>
  </div>
</template>

<script>


import HelloWorld from './components/HelloWorld'
import MyName from './components/MyName'
// You need a specific loader for CSS files

export default {
  name: 'App',
  components: {
    MyName,
    HelloWorld
  },
  data (){
    return {
      date:'2018-05-12T17:19:06.151Z'
    }
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
