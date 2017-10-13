<template>
  <div>
    <div>这里是最外层，页面导航不会动</div>
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>

<style lang="less" rel="stylesheet/less">

  @import "~font-awesome/css/font-awesome.css";
</style>
