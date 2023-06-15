<template>
  <view class="home-layout">
    <slot />

    <view class="description">home布局</view>
  </view>
</template>

<style lang="scss">
.home-layout {
  padding: 20rpx;

  .description {
    margin-top: 30rpx;
    text-align: center;
  }
}
</style>
