<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
    <div class="header">
      <div class="l-name">xxxx管理平台</div>
    </div>
    <div class="wrapper">
      <div class="left"></div>
      <div class="right"></div>
    </div>
  </div>
</template>

<style lang="less" scoped>
.container{
  width: 1920px;
  height: 1080px;
  display: flex;
  flex-direction: column;
}
.header{
  height: 80px;
  flex-shrink: 0;
  border: 1px solid;
  .l-name{
    font-weight: bold;
    font-size: 24px;
    color: #CFE2FF;
  }
}

.wrapper{
  padding: 20px;
  display: flex;
  flex: 1;
  border: 1px solid;
}
.left{
  width: 300px;
  height: 924px;
  border: 1px solid;
}
.right{
  width: 1582px;
  height: 835px;
  border: 1px solid;
}
</style>
