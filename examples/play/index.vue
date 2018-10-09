<template>
  <div style="margin: 20px;">
    <el-date-picker
      v-model="value3"
      range-separator="~"
      type="weekrange"
      placeholder="Pick a week">
    </el-date-picker>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        value3: '',
      }
    }
  };
</script>
<style>
.el-date-editor.el-input, .el-date-editor.el-input__inner {
  width: 250px;
}
</style>
