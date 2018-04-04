<template>
  <div>
    <tabbar>
    
      <tabbar-item selected>
        <img slot="icon" src="../static/icon/shouye.png">
        <span slot="label">首页</span>
      </tabbar-item>
  
      <tabbar-item>
        <img slot="icon" src="../static/icon/shujia.png">
        <span slot="label">书架</span>
      </tabbar-item>
      <tabbar-item  link="HelloWorld">
        <img slot="icon" src="../static/icon/shufang.png">
        <span slot="label">书房</span>
      </tabbar-item>
      <tabbar-item badge="">
        <img slot="icon" src="../static/icon/fanxian.png">
        <span slot="label">发现</span>
      </tabbar-item>
       <tabbar-item badge="">
        <img slot="icon" src="../static/icon/wode.png">
        <span slot="label">我的</span>
      </tabbar-item>
    </tabbar>
  </div>
</template>

<script>
import { Tabbar, TabbarItem, Group, Cell } from 'vux'

export default {
  components: {
    Tabbar,
    TabbarItem,
    Group,
    Cell
  }
}
</script>

<style type="text/css">
	.weui-tabbar {
		margin-left: -8px;
	}
		a {
		text-decoration: none;
		}
</style>