<!-- 主页面 -->
<template>
  <el-config-provider :locale="locale">
    <router-view />
  </el-config-provider>
</template>

<script setup>
import zhCn from "element-plus/dist/locale/zh-cn";;
let locale = zhCn;
</script>
