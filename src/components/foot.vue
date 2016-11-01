<template>
  <div class="foot">
    <!-- <h1>{{ msg }}</h1> -->
    <ul>
      <li>首页</li>
      <li >{{msg}}</li>
      <li>数据</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'foot',
  data () {
    return {
      msg: '新闻'
    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.foot{
  z-index: 999;
  position: fixed;
  bottom: 0;
  z-index: 999;
  width: 100%;
  background: #EFEFEF;
}

ul{
  display: flex;
}
li{
    flex: 1;
    float: left;
    line-height: 1.8rem;
    text-align: center;
    padding-top: 2.2rem;
    color: #6a6a6a;
    font-size: 10px;
    cursor: pointer;
    background: url(http://ftp452149.host548.zhujiwu.me/Demo/iwifi/images/menu01.png) no-repeat center 6px;
    background-size: 25px 25px;
}

a {
  color: #42b983;
}
</style>