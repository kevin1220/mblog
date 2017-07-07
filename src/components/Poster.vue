<template>
  <el-row>
    <el-col :span="12" v-for="(o, index) in 1" :key="o" :offset="6">
      <el-card :body-style="{ padding: '0px' }">
        <img src="../assets/poster.jpg" class="image">
        <div class="card-title-box">
          <span class="card-caption">技术人生</span>
          <div class="bottom clearfix">
            <em class="desc">多年来的工作和学习沉淀都在这里了</em>
          </div>
        </div>
      </el-card>
    </el-col>
  </el-row>
</template>

<style>
  .card-caption {
    color:#CCFFFF;
  }
  .card-title-box {
    padding: 14px;
    position: absolute;
    bottom: 14px;
  }
  .desc {
    font-size: 13px;
    color: #999;
  }
  
  .bottom {
    margin-top: 13px;
    line-height: 12px;
  }

  .image {
    width: 100%;
    display: block;
    position: relative;
  }

  .clearfix:before,
  .clearfix:after {
      display: table;
      content: "";
  }
  
  .clearfix:after {
      clear: both
  }
</style>

