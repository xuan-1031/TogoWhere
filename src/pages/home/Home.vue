<template>
    <div class="home"> 
        <!-- <router-link to="/list">列表页</router-link> -->
        <HomeHeader></HomeHeader>
        <home-swiper></home-swiper>
        <home-icons></home-icons>
    </div>
</template>

<script>
    import HomeHeader from './components/Header'
    import HomeSwiper from './components/Swiper'
    import HomeIcons from './components/Icons'
    export default {
        name: 'Home',
        components: {
            HomeHeader,
            HomeSwiper,
            HomeIcons
        }
    }
</script>

<style lang="scss" scoped>

</style>