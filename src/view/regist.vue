<template>
  <div>
    <button @click="back">返回</button>
    11111   
  </div>
</template>
<script>
export default {
  date() {
    return {};
  },
  methods: {
    back() {
      this.$router.push("./");
    },
  },
};
</script>
<style scoped>
button {
  width: 50px;
  height: 50px;
}
</style>