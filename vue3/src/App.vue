<template>
  <div id="app_wrap">
      <div id="header">
        <div class="title">YiShu's album</div>
        <div class="tools">
           <div class="avator"></div>
        </div>
      </div>
  </div>
</template>

<script setup lang="ts">

</script>
<style  lang="less" scoped>
#app_wrap {
  height: 100%;
  width: 100%;
  background: #FFF8ED;
  #header{
    height: 50px;
    width: 100%;
    background: #F4F5F0;
    line-height: 50px;
    display: flex;
    justify-content: space-between;
    .title{
      font-weight: 700;
      margin-left: 40px;
      font-size: 18px;
    }
  }
}
</style>
