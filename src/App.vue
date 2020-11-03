<template>
  <el-container>
    <el-header class="header">Header</el-header>
    <el-container class="content">
      <el-aside width="200px" class="aside">
        <LHMenu/>
      </el-aside>
      <el-main class="main">Main</el-main>
    </el-container>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script>
import LHMenu from './components/LHMenu'
export default {
  components: {
    LHMenu,
  }
}
</script>

<style lang="scss">
.header {
  height: 15vh;
}
.content {
  .aside {
    width: 20vw;
  }
  .main {
    flex: 1 1 auto;
  }
}
</style>
