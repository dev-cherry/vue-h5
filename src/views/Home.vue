<!--
 * @Description: 
 * @Author: zhongyuanrui
 * @Date: 2019-11-18 21:17:30
 * @LastEditors: zhongyuanrui
 * @LastEditTime: 2019-11-18 23:14:01
 -->
<template>
  <div class="home">
    <HelloWorld />
    <LabelItem />
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";
import LabelItem from "@/components/LabelItem.vue";

export default {
  name: "home",
  components: {
    HelloWorld,
    LabelItem
  }
};
</script>
