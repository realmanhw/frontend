<template>
    <div class="newhome">
        <el-container>
            <el-header>
            <HeadBar></HeadBar>
            </el-header>
            <el-container>
                <el-aside width="20%">Aside</el-aside>
                <el-main >Main</el-main>
                <el-aside width="20%">Aside</el-aside>
            </el-container>
            <el-footer>Footer</el-footer>
        </el-container>
    </div>
</template>

<script>

import HeadBar from "@/components/HeadBar";

    export default {
      name: "NewHome",
      components: {HeadBar}
    }
</script>

<style scoped>
    .el-header, .el-footer {
        background-color: #2b72cf;
        color: #333;
        line-height: 30px;
        padding: 8px 0px;
    }

    .el-aside {
        background-color: #e5a786;
        color: #333;
        text-align: center;
        line-height: 650px;
    }

    .el-main {
        background-color: #e9eef3;
        color: #333;
        text-align: center;
        line-height: 160px;
    }
</style>
