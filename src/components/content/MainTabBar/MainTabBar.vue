<template>
  <tab-bar>
    <tab-bar-item path="/home">
      <img slot="item-icon" src="~assets/img/home-deactivated.svg">
      <img slot="item-icon-active" src="~assets/img/home-activated.svg">
      <template v-slot:item-text><div>首页</div></template>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <img slot="item-icon" src="~assets/img/category-deactivated.svg">
      <img slot="item-icon-active" src="~assets/img/category-activated.svg">
      <template #item-text><div>分类</div></template>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img slot="item-icon" src="~assets/img/cart-deactivated.svg">
      <img slot="item-icon-active" src="~assets/img/cart-activated.svg">
      <template v-slot:item-text><div>购物车</div></template>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img slot="item-icon" src="~assets/img/my-deactivated.svg">
      <img slot="item-icon-active" src="~assets/img/my-activated.svg">
      <template v-slot:item-text><div>我的</div></template>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "components/common/tabbar/TabBar";
  import TabBarItem from "components/common/tabbar/TabBarItem";
    export default {
        name: "MainTabBar",
      components:{
        TabBar,
        TabBarItem
      }
    }
</script>

<style scoped>

</style>
