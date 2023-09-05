<template>
  <el-container style="height: 100vh">
    <el-header></el-header>
    <el-scrollbar>
      <el-main
        style="--el-main-padding: 32px 160px; overflow: hidden"
        class="bg-[#ecebed]"
        ><router-view></router-view
      ></el-main>
    </el-scrollbar>
  </el-container>
</template>
