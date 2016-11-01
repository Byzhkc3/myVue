<template>
  
  <div id="app">
  <top></top>
    <hello></hello>
    <list></list>
    <!-- <img src="./assets/logo.png"> -->
    <yali></yali>
    <foot></foot>
  </div>
  
</template>

<script>
import Hello from './components/Hello'
import yali from './components/yali'
import foot from './components/foot'
import top from './components/top'
import list from './components/list'
export default {
  name: 'app',
  components: {
    Hello,
    yali,
    foot,
    top,
    list
  }
}
</script>

<style>

h1,h2,h3{
  margin: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-bottom: 4rem;
  margin-top: 4rem;
  background-color: yellow;
  overflow-y: auto
}
ul,li{
 margin: 0;
 padding: 0;
  list-style: none;
}

</style>
