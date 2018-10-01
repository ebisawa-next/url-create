<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <p class="osushi">おしゅし！</p>
    <Input />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Input from './components/atoms/form/input'

export default {
  name: 'App',
  components: {
    HelloWorld, Input
  }
}
</script>

<style lang="scss" scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.osushi {
  font-size: 1.4rem;
}
</style>
