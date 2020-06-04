<template>
  <div class="home">
    <h1 class="title">Cup of Codes</h1>
    <div class="logo-area">
      <img class="logo" src="../assets/newCup3.png" alt="Cup of codes logo" />
    </div>
    <h4 class="subtitle">
      <!-- A Vue JS Project by <span class="author">Meriel Almoro</span> -->
      A Vue JS Project by <span class="author">~/meriel_almoro</span>
    </h4>

    <div style="margin-top: 15%; margin-bottom: 0px;">
      <el-row
        :gutter="0"
        style="margin: 0; align-items: center;display: flex; justify-content: center;"
      >
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <img
              src="../assets/thumbnails/1.jpg"
              style="width: 100%; height: 100%"
            /></div
        ></el-col>
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <img
              src="../assets/thumbnails/2.jpg"
              style="width: 100%; height: 100%"
            /></div
        ></el-col>
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <img
              src="../assets/thumbnails/3.jpg"
              style="width: 100%; height: 100%"
            /></div
        ></el-col>
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <img
              src="../assets/thumbnails/4.jpg"
              style="width: 100%; height: 100%"
            /></div
        ></el-col>
      </el-row>
      <el-row
        :gutter="0"
        style="margin: 0;align-items: center;display: flex; justify-content: center;"
      >
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <div class="mt-5">
              <img
                src="../assets/thumbnails/5.jpg"
                style="width: 100%; height: 100%"
              />
            </div></div
        ></el-col>
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <img
              src="../assets/thumbnails/6.jpg"
              style="width: 100%; height: 100%"
            /></div
        ></el-col>
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <img
              src="../assets/thumbnails/1.jpg"
              style="width: 100%; height: 100%"
            /></div
        ></el-col>
        <el-col :span="6" style="margin: 0;"
          ><div class="grid-content ">
            <img
              src="../assets/thumbnails/2.jpg"
              style="width: 100%; height: 100%"
            /></div
        ></el-col>
      </el-row>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home"
};
</script>
