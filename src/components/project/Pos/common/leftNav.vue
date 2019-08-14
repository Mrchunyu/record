<!--  -->
<template>
<div class='leftNav'>
  <ul>
    <li>
      <i class="icon iconfont icon-goumai"></i>
      <div>收银</div>
    </li>
    <li>
      <i class="icon iconfont icon-dianpu"></i>
      <div>店铺</div>
    </li>
    <li>
      <i class="icon iconfont icon-hanbao"></i>
      <div>商品</div>
    </li>
    <li>
      <i class="icon iconfont icon-huiyuanqia"></i>
      <div>会员</div>
    </li>
    <li>
      <i class="icon iconfont icon-wo"></i>
      <div>统计</div>
    </li>
  </ul>
</div>
</template>

<script>
//这里可以导入其他文件（比如：组件，工具js，第三方插件js，json文件，图片文件等等）
//例如：import 《组件名称》 from '《组件路径》';

export default {
//import引入的组件需要注入到对象中才能使用
components: {},
data() {
//这里存放数据
return {

};
},
//监听属性 类似于data概念
computed: {},
//监控data中的数据变化
watch: {},
//方法集合
methods: {

},
//生命周期 - 创建完成（可以访问当前this实例）
created() {

},
//生命周期 - 挂载完成（可以访问DOM元素）
mounted() {

},
beforeCreate() {}, //生命周期 - 创建之前
beforeMount() {}, //生命周期 - 挂载之前
beforeUpdate() {}, //生命周期 - 更新之前
updated() {}, //生命周期 - 更新之后
beforeDestroy() {}, //生命周期 - 销毁之前
destroyed() {}, //生命周期 - 销毁完成
activated() {}, //如果页面有keep-alive缓存功能，这个函数会触发
}
</script>
<style>
.leftNav {
  color: #fff;
  font-size: 10px;
  height: 100%;
  background-color: #1D8ce0;
  float: left;
  width: 5%;
}
.iconfont {
  font-size: 24px;
}
.leftNav li {
  list-style: none;
  text-align: center;
  border-bottom: 1px solid #20a0ff;
  padding: 10px;
}
</style>
