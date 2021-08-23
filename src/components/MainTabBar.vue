<template>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="orange">
        <img slot="item-icon"  src="@/assets/img/tabber/小型猫窝.png">
        <img slot="item-active-icon" src="@/assets/img/tabber-active/猫粮.png" >
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="red">
        <img slot="item-icon" src="@/assets/img/tabber/猫包.png">
        <img slot="item-active-icon" src="@/assets/img/tabber-active/洗浴.png" >
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="orange">
        <img slot="item-icon" src="@/assets/img/tabber/毛线球.png">
        <img slot="item-active-icon" src="@/assets/img/tabber-active/大排梳.png" >
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="orange">
        <img slot="item-icon" src="@/assets/img/tabber/猫咪.png">
        <img slot="item-active-icon" src="@/assets/img/tabber-active/便便.png" >
        <div slot="item-text">我的</div></tab-bar-item>       
    </tab-bar>
</template>

<script>

import TabBar from './tabbar/TabBar.vue'
import TabBarItem from './tabbar/TabBarItem.vue'

export default {
  name: 'VueMaintabbar',
  components:{
    TabBar,
    TabBarItem,
  }
  
};
</script>

<style>

</style>
