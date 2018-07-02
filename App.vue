<template>
  <view class="container">
    <text class="welcome">{{message}}</text>
  </view>
</template>

<script>
  export default {
    data: function() {
      return {
        message: "Welcome to Vue Native!!"
      }
    }
  }
</script>

<style>
.container {
  background-color: #333;
  align-items: center;
  justify-content: center;
  flex: 1;
}
.welcome {
  color: white;
  font-size: 20px;
  margin: 20px;
}
</style>