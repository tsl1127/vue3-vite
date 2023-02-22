<script setup>
const name = ref("isboyjc");
</script>
<template>
  <div>hello {{ name }}, this is helloworld components</div>
  <icon-ep-alarm-clock class="" />
  <icon-home-copy class="" />
  <icon-home-download class="" />
  <button
    class="bg-blue-400 hover:bg-blue-500 text-sm text-white font-mono font-light py-2 px-4 rounded border-2 border-blue-200 dark:bg-blue-500 dark:hover:bg-blue-600"
  >
    Button
  </button>
  <button
    bg="blue-400 hover:blue-500 dark:blue-500 dark:hover:blue-600"
    text="sm white"
    font="mono light"
    p="y-2 x-4"
    border="2 rounded blue-200"
  >
    Button2
  </button>
  <button class="btn-style">Button3</button>
</template>

<style scoped>
.btn-style {
  @apply bg-blue-400 text-sm text-white font-mono font-light py-2 px-4 rounded border-2 border-blue-200;
  @apply hover:bg-blue-500;
  @apply dark:bg-blue-500 dark:hover:bg-blue-600;
}
</style>
