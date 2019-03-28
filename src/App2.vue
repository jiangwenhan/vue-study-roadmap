<template>
  <div id="app2">
    <p>
      <span v-bind:title="message">鼠标悬停几秒钟查看此处动态绑定的提示信息！</span>
    </p>
  </div>
</template>

<script>
export default {
  name: "App2",
  data: function() {
    return {
      message: "页面加载于 " + new Date().toLocaleString()
    };
  }
};
</script>

<style scoped>
</style>
