<template>
  <scroll-bar>
    <el-menu class="el-menu-vertical-demo">
      <el-submenu index="1">
        <template slot="title">
          <span>数据库</span>
        </template>
        <el-menu-item-group>
          <template slot="title"><div></div></template>
          <el-menu-item index="1-1">选项1</el-menu-item>
          <el-menu-item index="1-2">选项2</el-menu-item>
        </el-menu-item-group>
      </el-submenu>
    </el-menu>
  </scroll-bar>
</template>

<script>
export default {
  name: 'lh-menu',
}
</script>
<style>
</style>
