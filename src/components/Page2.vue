<template>
  <div class="hello">

    <h1>这里是页面2了</h1>
    <div class="main">
      回到
      <router-link to="/">page1</router-link>
    </div>
  </div>
</template>

<script>

  import NavBar from "./NavBar.vue"
  import SideBar from "./SideBar.vue"

  export default {
    data() {
      return {}
    },
    components: {
      NavBar,
      SideBar
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" rel="stylesheet/less">

  .main {

    margin-left: 200px;
    margin-top: 80px;
  }
</style>
