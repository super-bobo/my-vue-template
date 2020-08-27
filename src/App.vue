<template>
  <div id="app">
    <div class="center">
      <img src="@/assets/images/logo.png" />
      <div class="demo">
        <el-button>Hello</el-button>
      </div>
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {}
};
</script>

<style lang="scss" scoped>
.center {
  margin-top: 120px;
  text-align: center;
}
.demo {
  margin: 20px auto;
}
</style>
