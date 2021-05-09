<template>
  <div id="app">
    <!-- 每次路由跳转都会重新渲染页面，加上keep=alive就是让其缓存起来，跳转的时候渲染页面速度就快 -->
    <keep-alive>
      <router-view />
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style scoped>
</style>
