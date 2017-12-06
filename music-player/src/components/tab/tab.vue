<template>
  <div class="tab">
    <router-link tag="div" to="/recommend"><span>推荐</span></router-link>
    <router-link tag="div" to="/singer"><span>歌手</span></router-link>
    <router-link tag="div" to="/rank"><span>排行</span></router-link>
    <router-link tag="div" to="/search"><span>搜索</span></router-link>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
.tab{
  display: flex;
  justify-content: space-around;
}
.tab span{
  display: block;
  font-size: 0.6rem;
  color: #333;
  height: 1.5rem;
  line-height: 1.5rem;
}
.router-link-active span{
  color: red;
  border-bottom: 1px solid red;
}
</style>