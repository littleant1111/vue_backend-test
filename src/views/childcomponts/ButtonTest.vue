<template>
  <div class="button">
    <el-row>
      <el-button @click="myclick">默认按钮</el-button>
      <el-button type="primary" >主要按钮</el-button>
      <el-button type="success">成功按钮</el-button>
      <el-button type="info">信息按钮</el-button>
      <el-button type="warning">警告按钮</el-button>
      <el-button type="danger">危险按钮</el-button>
    </el-row>
  </div>
</template>

<script>
  export default {
    name: "ButtonTest",
    methods: {
      myclick(){
        alert('aaaaaaaaaa')
      }
    }
  }
</script>

<style scoped>

</style>