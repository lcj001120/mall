<template>
  <div class="nav-bar">
  <div class="left"><slot name="left"></slot></div>
  <div class="center"><slot name="center">购物车</slot></div>
  <div class="right"><slot name="right"></slot></div>
  </div>
</template>

<style scoped>
.nav-bar {
  display:flex;
  line-height: 44px;
  text-align: center;
  box-shadow: 0 1px 1px rgba(100,100,100.0.1) ;
}
.left,.right{
  width:60px;
  
}
.center{
  flex: 1;
}
</style>

<script>

export default({
})
</script>
