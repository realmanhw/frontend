<template>
  <div>
    <el-container>
      <el-aside width="80%">Aside</el-aside>
      <el-aside class="user" width="20%" >
        <el-image src="http://www.yuepaijie.cn/img/touxiang.jpg" fit="fill"></el-image>
        我的名字
      </el-aside>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "HeadBar",
}

</script>

<style lang="scss" scoped>
  @mixin
  header-align() {
    position: relative;
    top: 5px;
  }
  .el-container{
    font-weight: bold;
  }
  .el-image{
    border-radius: 15px;
    width: 30px;
    height: 30px;
    vertical-align: middle;
  }
  .el-aside{
    @include
    header-align;
    padding-left: 20px;
  }
  .user{
    @include
    header-align;
    text-align: right;
    padding-right: 20px;
  }
</style>
