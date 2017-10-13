<template>
  <div class="navi-bar">
    Navi-bar<b style="color:red">{{title}}</b>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        "title": "世界你好,Hello World"
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" rel="stylesheet/less">

  .navi-bar {
    background: palegreen;
  }
</style>
