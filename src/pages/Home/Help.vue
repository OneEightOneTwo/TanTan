<template>
  <div>
      <Theader :showHelp="true">新手引导</Theader>

  </div>
</template>

<script>
// 引入头部组件
import Theader from "../../components/Theader.vue";

export default {
    name: "app",
  components: {
    Theader,
  }

};
</script>

<style lang="scss" scoped>
</style>