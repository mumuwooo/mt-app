<template>
  <div class="header">
   <!-- 顶部通栏 -->
  <div class="top-wrapper">
    <div class="back-wrapper">
      <span class="icon-arrow_lift"></span>
    </div>
    <form class="search-wrapper">
      <span class="search-icon"></span>
      <input type="text" class="search-bar" placeholder="搜索店内商品">
    </form>
    <div class="more-wrapper">
      <a href="#" class="spelling-bt">拼单</a>
      <div class="more-btn">
        <i class="s-radius"></i>
        <i class="s-radius"></i>
        <i class="s-radius"></i>
      </div>
    </div>
  </div>
   <!-- 主题内容 -->

   <!-- 公告内容 -->
  </div>
</template>

<script>
  export default{
    props:{
      poiInfo:{
        type:Object,
        default:{}
      }
    }
  }
</script>

<style scoped>

</style>
