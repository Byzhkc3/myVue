<template>
  <div class="hello">
    <!-- 毛玻璃 -->
    <div class="container ">
      <div class="glass"></div>
    </div>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

img{
  width: 100%;
  height: 100%;
}
.container{   
  margin: 0 auto;
   width: 100%;   
   height: 30rem;   
   background-image: url(../assets/1.jpg); 
   background-repeat: no-repeat; 
   background-size:100% 100%;
   background-position: center;
   /*background-attachment: fixed;   */
   overflow: hidden;   
   }
.glass{   
  width: 100%;  
  height: 30.2rem;   
  background: inherit;   
  -webkit-filter: blur(5px);   
  -moz-filter: blur(5px);   
  -ms-filter: blur(5px);   
  -o-filter: blur(5px);   
  filter: blur(5px);   
  filter: progid:DXImageTransform.Microsoft.Blur(PixelRadius=4, MakeShadow=false);   
}   
a {
  color: #42b983;
}
</style>
