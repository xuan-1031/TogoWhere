<template>
    <div class="home"> 
        <!-- <router-link to="/list">列表页</router-link> -->
        <HomeHeader></HomeHeader>
    </div>
</template>

<script>
    import HomeHeader from './components/Header'
    export default {
        name: 'Home',
        components: {
            HomeHeader
        }
    }
</script>

<style lang="scss" scoped>

</style>