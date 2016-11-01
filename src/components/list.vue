<template>
  <div class="list">
    <ul>
      <li>100</li>
      <li>2</li>
      <li>3</li>
      <li>4</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'list',
  data () {
    return {
      msg: '历史推送'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  ul,li{
    margin: 0;
    padding: 0;
    list-style: none;
  }
  ul{
    /*margin-top: 4rem;*/
  }
  li{
    height: 4rem;
    background-color:#ccc;
  }
  li{
    margin-bottom: 0.8rem;
  }
  li:first-child{
    margin-top:1rem;
  }
  li:last-child{
    margin-bottom: 0;
  }
</style>