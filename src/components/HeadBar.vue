<template>
  <el-row :gutter="20">
    <el-col :span="6"><div class="grid-content bg-purple">button1</div></el-col>
    <el-col :span="6"><div class="grid-content bg-purple">button2</div></el-col>
    <el-col :span="6"><div class="grid-content bg-purple">button3</div></el-col>
    <el-col :span="6"><div class="grid-content bg-purple">button4</div></el-col>
  </el-row>
</template>

<script>
export default {
name: "HeadBar"
}
</script>

<style scoped>
.el-row {
  margin-top: 0px;
  margin-bottom: 0px;
  &:last-child {
    margin-bottom: 0;
  }
}
.el-col {
  border-radius: 4px;
}
.bg-purple-dark {
  background: #99a9bf;
}
.bg-purple {
  background: #d3dce6;
  padding: 0px;
  margin: 0px;
}
.bg-purple-light {
  background: #e5e9f2;
}
.grid-content {
  border-radius: 6px;
  min-height: 0px;
  padding: 0px;
  margin: 0px;
}
.row-bg {
  padding: 0px 0;
  background-color: #f9fafc;
}
</style>
