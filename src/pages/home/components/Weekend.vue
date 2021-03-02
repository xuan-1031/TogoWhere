<template>
    <div>
        <div class="recommend-title">周末去哪儿</div>
        <ul>
            <li class="item border-bottom" v-for='item of recommendList' :key='item.id'>
                <div class="item-img-wrapper">
                    <img class="item-img" :src="item.imgUrl" alt="">
                </div>
                <div class="item-info">
                    <p class="item-title">{{item.title}}</p>
                    <p class="item-desc">{{item.desc}}</p>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: 'HomeRecommend',
        data(){
            return{
                recommendList: [{
                    id: '0001',
                    imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_140x140_abb362a7.jpg',
                    title: '大连圣亚海洋世界',
                    desc: '浪漫大连首站，浪漫的海洋主题公园'
                },{
                    id: '0002',
                    imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_140x140_abb362a7.jpg',
                    title: '大连圣亚海洋世界',
                    desc: '浪漫大连首站，浪漫的海洋主题公园'
                },{
                    id: '0003',
                    imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_140x140_abb362a7.jpg',
                    title: '大连圣亚海洋世界',
                    desc: '浪漫大连首站，浪漫的海洋主题公园'
                },{
                    id: '0004',
                    imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_140x140_abb362a7.jpg',
                    title: '大连圣亚海洋世界',
                    desc: '浪漫大连首站，浪漫的海洋主题公园'
                },{
                    id: '0005',
                    imgUrl: 'http://img1.qunarzz.com/sight/p0/1511/d2/d2aec2dfc5aa771290.water.jpg_140x140_abb362a7.jpg',
                    title: '大连圣亚海洋世界',
                    desc: '浪漫大连首站，浪漫的海洋主题公园'
                },]
            }
        }
    }
</script>

<style lang="stylus" scoped>
    @import '~styles/mixins.styl'
    .recommend-title
        margin-top: .2rem
        line-height: .8rem
        background: #eee
        text-indent: .2rem
    .item-img-wrapper
        overflow: hidden;
        height: 1rem;
        padding-bottom: 25.09%
    .item-img    
        width: 100%
    .item-info
        padding: .1rem
        .item-title
            line-height: .54rem
            font-size: .32rem
            ellipsis()
        .item-desc
            line-height: .4rem
            color: #ccc
            ellipsis()
</style>