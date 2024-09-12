<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="container">
    <div class="header"></div>
    <div class="wrapper">
      <div class="left"></div>
      <div class="right"></div>
    </div>
  </div>
</template>

<style scoped>
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
