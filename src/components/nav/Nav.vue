<template>
  <div class="nav">
   <router-link to="/goods" class="nav-item">点餐
   <i class="line"></i>
   </router-link>
   <router-link to="/ratings" class="nav-item">评价
   <i class="line"></i>
   </router-link>
   <router-link to="/seller" class="nav-item">商家
   <i class="line"></i>
   </router-link>
  </div>
</template>

<script>

</script>

<style scoped>
.nav{
  display: flex;
  width: 100%;
  height: 40px;
  line-height: 40px;
  border-bottom: 1px solid #e4e4e4;
}
.nav-item{
  flex: 1;
  text-align: center;
  text-decoration: none;
  color: #666666;
  position: relative;
}
.nav .active{
  color: #ffbb22;
}
.nav .active .line{
  background: #ffbb22;
  width: 20px;
  height: 2px;
  display: inline-block;
  position: absolute;
  left: 50%;
  bottom: 0;
  margin-left: -10px;
}
</style>
