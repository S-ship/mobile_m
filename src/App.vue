<template>
    <div>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>\
    <div class="big"></div>
    <router-view/>
    </div>
</template>

<style lang="less">
.big {
  width: 200px;
  height: 200px;
  background-color: pink;
}
</style>
