<script setup lang="ts">
defineProps({
  settingFlag: {
    type: Boolean
  }
})

</script>


<template>
  <div class="setting_wrap" v-show="settingFlag">
    <div class="colorChoose">
      <h3>颜色选择</h3>
      <input type="color">
    </div>
  </div>
</template>

<style scoped lang="less">
.setting_wrap {
  width: 40%;
  height: 100vh;
  background-color: #ffffff;
  position: absolute;
  right: 0;
  top: 0;
  opacity: 0.5;
  padding-left: 30px;
  .colorChoose {
    margin-top: 30px;
  }
}
</style>