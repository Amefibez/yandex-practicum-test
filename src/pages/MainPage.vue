<template>
  <div class="flex flex-col justify-start items-center">
    <div class="h-[100vh] w-[70vw] bg-white p-8 text-[32px] font-bold text-[#f2c522]">
      <el-scrollbar>
        <div class="flex flex-col gap-4 h-[30vh]">
          <UserCard />
          <SkillsComponent />
        </div>
        <el-divider />
        <MyStory />
        <el-divider />
        <CSSFeatureVideoContainer/>
      </el-scrollbar>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
