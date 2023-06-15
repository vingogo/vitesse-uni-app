<template>
  <view class="default-layout">
    <slot />

    <view class="description">默认布局</view>
  </view>
</template>

<style lang="scss">
.default-layout {
  .description {
    margin-top: 30rpx;
    text-align: center;
  }
}
</style>
