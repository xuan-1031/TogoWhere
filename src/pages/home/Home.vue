<template>
    <div class="home"> 
        <!-- <router-link to="/list">列表页</router-link> -->
        <HomeHeader></HomeHeader>
        <home-swiper></home-swiper>
    </div>
</template>

<script>
    import HomeHeader from './components/Header'
    import HomeSwiper from './components/Swiper'
    export default {
        name: 'Home',
        components: {
            HomeHeader,
            HomeSwiper
        }
    }
</script>

<style lang="scss" scoped>

</style>