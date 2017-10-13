<template>
  <div class="side-bar">
    <div @click="open=!open">
      菜单
      <span>
                <i class="fa fa-caret-right" v-show="!open"></i>
                <i class="fa fa-caret-down" v-show="open"></i>
            </span>
    </div>
    <div v-show="open">
      <div>条目1</div>
      <div>条目2</div>
      <div>条目3</div>
      <div>条目4</div>
      <div>条目5</div>
    </div>
  </div>
</template>

<script>
  export default {
    data: function () {
      return {
        open: false
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" rel="stylesheet/less">

  .side-bar {
    position: fixed;
    left: 0;
    top: 60px;
    bottom: 0;
    width: 200px;
    background: pink;
  }
</style>
