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
@import "../../common/css/icon.css";

.header{
  height: 160px;
  padding-top: 20px;
}
.header .top-wrapper{
  position: relative;
}
.header .top-wrapper .back-wrapper{
  width: 50px;
  height: 31px;
  position: absolute;
  left: 0;
  top: 0;
  text-align: center;
  line-height: 31px;

}
.header .top-wrapper .search-wrapper{
  width: 100%;
  padding: 0 104px 0 50px;
  height: 31px;
  box-sizing: border-box;
}
.header .top-wrapper .search-wrapper .search-icon{
  width: 28px;
  height: 31px;
  /* background: url(./img/search.png) no-repeat 11px center; */
  position: absolute;
}
.header .top-wrapper .search-wrapper .search-bar{
  width: 100%;
  height: 31px;
  border: 0;
  box-sizing: border-box;
  background: #cdcdcc;
  border-radius: 25px;
  padding-left: 28px;
  outline: none;
}
.header .top-wrapper .more-wrapper{
  width: 65px;
  height: 24px;
  position: absolute;
  right: 0;
  top: 0;
  padding: 7px 15px 0 24px;
}
.header .top-wrapper .more-wrapper .spelling-bt {
  width: 30px;
  height: 17px;
  line-height: 17px;
  font-size: 10px;
}
</style>
