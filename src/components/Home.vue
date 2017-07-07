<template>
<div class="container">
  <Poster></Poster>
  <el-col :span="12" :offset="6">
    <el-col :span="4" :offset="0">
      <Nav-my></Nav-my>
    </el-col>
  </el-col>
</div>
</template>
<script>
  import Poster from './Poster'
  import Nav from './Nav'
  export default {
    components: {
      Poster,
      'Nav-my': Nav
    }
  }
</script>
