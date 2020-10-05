<template>
  <div id="app">
<!--      <router-link to="/">NewHome</router-link> |-->
<!--      <router-link to="/about">About</router-link> |-->
<!--      <router-link to="/home">Home</router-link>-->
      <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  components: {

  }
}
</script>


<style>
html,body,#app,.el-container {
  font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
  font-size: 16px;
  color: #e9eef3;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 0px;
  margin:0px;
  height: calc(100vh - 65px);
}
</style>
