<template>
    <div class="navbar clearfix">
        <!-- <el-breadcrumb class="breadcrumb-container" separator-class="el-icon-arrow-right">
            <el-breadcrumb-item v-for="item in levelList" :key="item.path" :to="item.path">{{item.name}}</el-breadcrumb-item>
        </el-breadcrumb> -->
        <el-breadcrumb separator-class="el-icon-arrow-right">
        <el-breadcrumb-item >当前位置：首页</el-breadcrumb-item>
        <el-breadcrumb-item >目录分类</el-breadcrumb-item>
        <el-breadcrumb-item v-for="item in levelList" :key="item.path" :to="item.path">{{item.meta.title}}</el-breadcrumb-item>
   </el-breadcrumb>
    </div>
</template>
 
<script>
    export default {
        name: 'Navbar',
        data() {
            return {
                levelList: []
            }
        },
        watch: {
            $route() {
                this.getBreadcrumb()
            }
        },
        created(){
            this.getBreadcrumb()
        },
        methods:{
            getBreadcrumb() {
                console.log(this,this.$route,'route')
                //$route.matched一个数组 包含当前路由的所有嵌套路径片段的路由记录
                let matched = this.$route.matched.filter(item => item.name)
                // console.log(matched)
                // const first = matched[0];
                // if (first && first.name.trim().toLocaleLowerCase() !== 'Dashboard'.toLocaleLowerCase()) {
                //     matched = [{ path: '/dashboard', meta: { title: 'dashboard' }}].concat(matched)
                // }
                this.levelList = matched
            }
        }
    }
</script>
<style scoped>
</style>