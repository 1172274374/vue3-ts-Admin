<template>
  <div class="box">
   <div class="hhh"></div>
  </div>
</template>

<script lang="ts" setup>

</script>

<style lang="less" scoped>
  @import '@/styles/theme.less';

  .themeBgColor(box);

  .box {
    display: flex;
    padding: 12px;
    width: 100%;
    height: auto;
    flex-direction: column;

    .hhh{
      width: 20%;
      height: 20vw;
      
      background: red;
    }

  }
</style>