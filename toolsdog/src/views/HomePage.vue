<script setup>
const handleClickMini = () => {
  AMessage.info("hello isboyjc, click mini AButton!");
};
</script>
<template>
  <div>hello isboyjc, This is toolsdog home page!</div>
  <a-space>
    <a-button type="primary" size="mini" @click="handleClickMini"
      >Mini</a-button
    >
    <a-button type="primary" size="small">Small</a-button>
    <a-button type="primary">Medium</a-button>
    <a-button type="primary" size="large">Large</a-button>
  </a-space>
  <!-- 这里 -->
  <HelloWorld />
</template>
<style scoped lang="scss"></style>
