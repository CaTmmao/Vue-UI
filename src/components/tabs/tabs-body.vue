<template>
  <div class="tabs-body">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "v-tabs-body",
  //tabs组件中用provide选项提供了eventBus，其他子孙组件需要用inject注入eventBus
  inject: ["eventBus"]
};
</script>

<style scoped lang="scss">
.tabs-body {
}
</style>
