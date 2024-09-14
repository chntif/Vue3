<template>
  <header class="top">
    <div>我的订单</div>
    <div>购物车</div>
    <div>个人中心</div>
    <div><span>登录</span> | <span>注册</span></div>
  </header>
  <!-- <router-view></router-view> -->
</template>

<script setup>
</script>

<style scoped lang="scss">
h1 {
  text-align: center;
  line-height: 1;
}

.top {
  display: flex;
  flex-direction: row;
  justify-content: end;
  line-height: 1;
  font-size: 16px;
  border: 1px solid red;
  width: 100%;

  &div {
    margin-left: 20px;
  }
}

@media (min-width: 1024px) {
  // 根据几列布局来动态变化布局方式
}
</style>