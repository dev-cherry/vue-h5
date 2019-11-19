<!--
 * @Description: 
 * @Author: zhongyuanrui
 * @Date: 2019-11-18 21:17:30
 * @LastEditors: zhongyuanrui
 * @LastEditTime: 2019-11-18 22:53:09
 -->
<template>
  <div class="box">
    <div class="inner">我是div1</div>
    <div class="inner">我是div2</div>
    <div class="inner">我是div3</div>
    <div class="inner">我是div4</div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>

<style scoped lang="scss">
.box {
  display: flex;
  width: 100%;
  min-height: 200px;
  border: 1px solid #ccc;
  flex-wrap: wrap;
  flex-direction: column;
}
.inner {
  width: 300px;
  height: 50px;
  color: #fff;
  background: red;
  text-align: center;
  margin: auto;
}
</style>
