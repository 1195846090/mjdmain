<template>
    <tab-bar>
        <tab-bar-item path="/home" activeColor="red">
            <i slot="item-icon" class="iconfont">&#xe609;</i>
            <i slot="item-icon-active" class="iconfont">&#xe60c;</i>
            <div slot="item-text">首页</div>
        </tab-bar-item>
        <tab-bar-item path="/category" activeColor="yellow">
            <i slot="item-icon" class="iconfont">&#xe617;</i>
            <i slot="item-icon-active" class="iconfont">&#xe60c;</i>
            <div slot="item-text">分类</div>
        </tab-bar-item>
        <tab-bar-item path="/cart" activeColor="green">
            <i slot="item-icon" class="iconfont">&#xe611;</i>
            <i slot="item-icon-active" class="iconfont">&#xe60c;</i>
            <div slot="item-text">购物车</div>
        </tab-bar-item>
        <tab-bar-item path="/profile">
            <i slot="item-icon" class="iconfont">&#xe610;</i>
            <i slot="item-icon-active" class="iconfont">&#xe60c;</i>
            <div slot="item-text">我的</div>
        </tab-bar-item>
    </tab-bar>
</template>

<script>
    import TabBar from '../tabbar/TabBar'
    import TabBarItem from '../tabbar/TabBarItem'
    export default {
        name: "MainTabBar",
        components: {
            TabBar,
            TabBarItem
        }
    }
</script>

<style scoped>

</style>