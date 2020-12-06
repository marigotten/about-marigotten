<template>
  <el-carousel class="carousel-wrapper" height="200px" direction="vertical" :autoplay="false">
    <!-- <el-carousel-item v-for="item in 4" :key="item"> -->
    <el-carousel-item class="carousel-slide">
      <el-row class="carousel-item">
        <el-col :span="12" class="carousel__img">
                <img alt="avator-marigotten" src="../static/avator.jpg">
        </el-col>

        <el-col :span="12">
            <h2>sample</h2>
        </el-col>
      </el-row>
    </el-carousel-item>

    <el-carousel-item class="carousel-slide">
      <el-row>
        <el-col :span="12">
                <img alt="avator-marigotten" src="../static/avator.jpg">
        </el-col>
        <el-col :span="12">
                        <h2>sample</h2>
        </el-col>
      </el-row>
    </el-carousel-item>

    <el-carousel-item class="carousel-slide">
      <!-- <el-row> -->
        <el-col :span="12">
          <el-image src="require('../static/avator.jpg')" lazy></el-image>
        </el-col>
        <el-col :span="12">
            <h2>sample</h2>
        </el-col>
      <!-- </el-row> -->
    </el-carousel-item>

  </el-carousel>
</template>

<style lang="scss">
.carousel-wrapper {
  width: 100%;
}
img {
  width: 100%;
}
  /* .el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 200px;
    margin: 0;
  }
  
  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }
  
  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
  .el-carousel__indicators--vertical {
    right: 0;
    top: 50%;
    transform: translateY(-50%);
} */
.el-carousel__indicator--vertical {
    padding: 4px 12px;
}
</style>