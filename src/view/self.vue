<template>
  <div id="app">
    <tabbar></tabbar>
    <button class="btn" @click="regist">注册</button>
    <button class="btn" @click="login">登录</button>
  </div>
</template>

<script>
import tabbar from '@/components/tabber/tabbar.vue';
export default {
  name: "App",
   components : {tabbar},
  date() {
    return {};
  },
  methods: {
    regist() {
      console.log(1);
      this.$router.push('./regist')
    },
    login(){
      console.log(2);
       this.$router.push('./login')
    }
  },
};
</script>

<style scoped>
.btn {
  width: 60px;
  height: 50px;
  text-align: center;
  line-height: 50px;
  font-size: 18px;
}
</style>