<template>
  <div id="home">
     <Header></Header>
     <tabbar></tabbar>
     nihao 
  </div>
</template>

<script>

import Header from '@/components/header'; 
// 引入组件
import tabbar from '@/components/tabber/tabbar.vue';
export default {
  name: 'home',
  components : {Header ,tabbar}
}
</script>

<style>

</style>