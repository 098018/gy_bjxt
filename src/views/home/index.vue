<template>
  <div class="fullScreenContainer">
    <h1 class="bjxt-title" @click="$router.push('/')">报价系统</h1>
    <el-container>
      <router-view />
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data() {
    return {

    }
  }
}
</script>

<style scoped>
  html,
  body,
  .fullScreenContainer {
    width: 100%;
    height: 100%;
  }

  .bjxt-title {
    text-align: center;
    font-weight: 700;
  }
</style>
