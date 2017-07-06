<template>
<div id="container">
  <Poster></Poster>
  <Nav></Nav>
</div>
</template>
<style type="text/css">
  #container{
    width:50%;
    margin-left: 25%;
  }
</style>
<script>
  import Nav from './Nav'
  import Poster from './Poster'
  export default {
    components: {
      Poster,
      Nav
    }
  }
</script>
