<template>
  <div class="navBox">
    <el-row type="flex" justify="center">
      <el-button type="success" @click="$router.push('/original')">原装主机</el-button>
      <el-button type="warning" @click="$router.push('/combine')">组装机</el-button>
    </el-row>
  </div>
</template>

<script>
export default {
  name: 'ProductLink'
}
</script>

<style lang="scss" scoped>
  .navBox {
    width: 100%;

    .el-button {
      min-width: 120px;
      margin: 10px 30px;
    }
  }
</style>
