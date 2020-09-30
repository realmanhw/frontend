<template>
    <div class="newhome">
        <el-container>
            <el-header>
            <HeadBar></HeadBar>
            </el-header>
            <el-container>
                <el-aside width="300px">Aside</el-aside>
                <el-main >Main</el-main>
                <el-aside width="300px">Aside</el-aside>
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
        background-color: #B3C0D1;
        color: #333;
        text-align: center;
        line-height: 40px;
        padding: 10px 320px;
    }

    .el-aside {
        background-color: #D3DCE6;
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

    body > .el-container {
        margin-bottom: 0px;
    }

    .el-container:nth-child(5) .el-aside,
    .el-container:nth-child(6) .el-aside {
        line-height: 260px;
    }

    .el-container:nth-child(7) .el-aside {
        line-height: 320px;
    }
</style>
