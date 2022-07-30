<template>
  <div id="app">
    <router-view />
    <h2>今日</h2>
    <!-- 首先在style导入
         然后使用字体类头 及 字体类 -->
    <div><i class="toutiao toutiao-guanbi"></i></div>
    <h1>头条</h1>
    <van-cell-group>
      <van-cell title="单元格" value="内容" />
      <van-cell title="单元格" value="内容" label="描述信息" />
    </van-cell-group>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
#app {
  h2 {
    font-size: 30px;
  }
  h1 {
    font-size: 50px;
  }
}
</style>
