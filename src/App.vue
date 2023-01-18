<template>
  <div id="app">
    <img alt="Vue logo" src="https://hashnode.com/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1672832508585%2FR5Xm4zw5t.png%3Fw%3D500%26h%3D500%26fit%3Dcrop%26crop%3Dfaces%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=1920&q=75">
    <HelloWorld msg="WELCOME TO MY WEBSITE"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
