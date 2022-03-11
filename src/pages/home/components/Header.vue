<template>
  <div class="header">
  <div class="header-left">
    <span class="iconfont-left">&#xe624;</span>
  </div>
    <div class="header-input">
      <span class="iconfont-left">&#xe632;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont-right">&#xe64a;</span>
    </div>
  </div>
</template>

<script>


export default {
  name: 'HomeHeader'
}
</script>

<style scoped>
.header {
  display: flex;
  height: 1rem;
  background:#151DC7;
  color: #ffffff
}
.header-left {
  margin-top:.35rem;
  width: 2.64rem;
  float: left
}
.header-input {
  flex: 1 ;
  height:.64rem;
  line-height:.64rem;
  margin-top:.2rem;
  margin-left: -1.8rem;
  background :#fff ;
  color: #ccc;
  border-radius: .1rem;
}
.header-right {
  margin-left:.21rem;
  margin-top: .35rem;
  margin-right: .2rem;
  min-width: .64rem;
  text-align: center;
  float: right
}
.iconfont-left{
  margin-left:.25rem;
  font-family:"iconfont" !important;
  font-size:16px;
  font-style:normal;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.iconfont-right{
  font-family:"iconfont" !important;
  font-size:8px;
  font-style:normal;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>

