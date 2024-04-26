<script setup lang=ts>
function click() {
  alert('1')
}
</script>

<template>
  <van-swipe-cell @click="click">
    <template #left>
      <van-button square type="primary" text="选择" />
    </template>   <van-cell :border="false" :title="1" value="内容" /> <template #right>
      <van-button square type="danger" text="删除" />
    </template>
  </van-swipe-cell>
</template>

<style lang="scss" scoped></style>
