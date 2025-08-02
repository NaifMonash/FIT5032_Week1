<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to My Vue.js App"/>
    <MyName />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyName from './components/MyName.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyName
  }
}
</script>

