<template>
  <div class="top">
    <!-- <i>&lt;</i> -->
    <i class="iconfont tab_wd icon-tab_wd"></i>
    <h2>{{ msg }}</h2>
  </div>
</template>

<script>
export default {
  name: 'top',
  data () {
    return {
      msg: '首页'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.top{
  z-index: 999;
  top: 0;
  position: fixed;
  height: 4rem;
  width: 100%;
  line-height: 4rem;
  background-color: #04ABFD;
  color: #fff;
}
i{
  height: 4rem;
  width: 2rem;
  position: absolute;
  top: 0;
  left: 0.5rem;
  font-size: 2rem;
}
h1{
  font-weight: normal;
}
</style>