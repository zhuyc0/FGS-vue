<template>
    <el-container>
        <el-header height="40">
            <MyHeader></MyHeader>
        </el-header>
        <el-main>
            <Info></Info>
        </el-main>
        <el-footer height="150px">
            <Footer></Footer>
        </el-footer>
    </el-container>
</template>

<script>
    import MyHeader from '@/components/MyHeader';
    import Footer from "@/components/Footer";
    import Info from "@/userinfo/views/Info";
    export default {
        name: "app",
        data() {
            return {
            }
        },
        components: {Info, MyHeader,Footer},
        methods: {
        }
    };
</script>

<style lang="scss">

</style>
