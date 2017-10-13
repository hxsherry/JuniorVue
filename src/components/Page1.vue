<template>
  <div class="hello">

    <NavBar></NavBar>
    <SideBar></SideBar>

    <div class="main">
      前往
      <router-link to="/page2">page2</router-link>
    </div>
  </div>
</template>

<script>

  import NavBar from "./NavBar.vue"
  import SideBar from "./SideBar.vue"

  export default {
    data() {
      return {

      }
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
