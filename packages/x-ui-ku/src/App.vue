<template>
  <div>
    <JSXButton>TSX Button</JSXButton>
    <XButton color="blue">蓝色按钮</XButton>
    <XButton color="green">绿色按钮</XButton>
    <XButton color="gray">灰色按钮</XButton>
    <XButton color="yellow">黄色按钮</XButton>
    <XButton color="red">红色按钮</XButton>

    <div>
      <XButton color="blue" round plain icon="search"></XButton>
      <XButton color="green" round plain icon="edit"></XButton>
      <XButton color="gray" round plain icon="check"></XButton>
      <XButton color="yellow" round plain icon="message"></XButton>
      <XButton color="red" round plain icon="delete"></XButton>
    </div>
  </div>
</template>

<script lang="ts">
import JSXButton from "./JSXButton/index";
import XButton from "./Button/Button";

export default {
  name: "App",
  components: {
    JSXButton,
    XButton,
  },
};
</script>
