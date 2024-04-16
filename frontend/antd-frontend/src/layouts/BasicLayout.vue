<template>
  <a-layout style="height: 400px">
    <a-layout-header>导航栏</a-layout-header>
    <a-layout>
      <a-layout-sider theme="dark">大纲</a-layout-sider>
      <a-layout-content>路由页面</a-layout-content>
    </a-layout>
    <a-layout-footer>底部信息</a-layout-footer>
  </a-layout>
  <router-view />
</template>

<style></style>
