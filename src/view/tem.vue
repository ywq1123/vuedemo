<template>
  <div id="tem">
     <Header></Header>
      <tabbar></tabbar>
  </div>
</template>

<script>
import Header from '@/components/header'; 
import tabbar from '@/components/tabber/tabbar.vue';
export default {
  name: 'tem',
  components : {Header ,tabbar}
}
</script>

<style>

</style>