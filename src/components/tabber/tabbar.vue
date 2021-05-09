<template>
  <div id="footer">
    <div class="footer">
        <router-link to="/" >
        <div class="box">
          <img src="../../assets/icon/home.png" alt="" />
          <span>首页</span>
        </div>
        </router-link>
         <router-link to="/tem">
        <div class="box">
          <img src="../../assets/icon/home.png" alt="" />
          <span>模板</span>
        </div>
         </router-link>
         <router-link to="/mytem">
        <div class="box">
          <img src="../../assets/icon/home.png" alt="" />
          <span>我的设计</span>
        </div>
         </router-link>
         <router-link to="/self">
        <div class="box">
          <img src="../../assets/icon/home.png" alt="" />
          <span>个人中心</span>
        </div>
         </router-link>
    </div>
  </div>
</template>
<script>
export default {
  name: "footerNav",
  Date() {
    return {};
  },
};
</script>
<style scoped>
.footer {
  width: 100%;
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100px;
  background: gainsboro;
}
.box {
  width: 24%;
  display: inline-block;
}
img {
  display: block;
  width: 20px;
  height: 20px;
  margin: 10px auto;
}
span {
  display: block;
  text-align: center;
}
a.router-link-sctive{
  color: red ;
}
</style>