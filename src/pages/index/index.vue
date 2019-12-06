<template>
  <div class="wrapper">
    <img class="image" src="">
    <button class="btn" >获取用户信息</button>
    <p class="userName">hello</p>
    <div class="start">
      <p>开启小程序之旅</p>
    </div>
  </div>
</template>
<script>
  export default {
      data() {
          return {

          }
      }
  }
</script>
<style>
  page{
    background-color: yellow;
  }
  .wrapper{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .image{
    width: 200rpx;
    height: 200rpx;
    border-radius: 50%;
    margin: 100rpx 0;
  }
  .userName{
    font-size: 32rpx;
    font-weight: bold;
    margin: 100rpx 0;
  }
  .start{
    border: 1rpx solid #eee;
    width: 280rpx;
    height: 80rpx;
    border-radius: 10rpx;
    line-height: 80rpx;
    text-align: center;
  }
</style>
