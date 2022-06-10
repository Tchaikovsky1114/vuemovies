<template lang="">
  <div class="container">
    <h1>Movie<span>Flex</span><br/><h2>Easy on search to wanna movies</h2></h1>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Rem unde rerum enim temporibus quia vel ullam alias, eligendi laudantium molestias quos itaque sequi harum dolorem architecto fugiat expedita, natus eveniet placeat totam repellendus est minus tenetur! Deleniti quia facilis praesentium!</p>

  </div>
</template>
<script>
export default {
  
}
</script>
<style lang="scss" scoped>
@import '../scss/main.scss';
  .container {
    padding-top: 40px;
  }
  h1{
    line-height: 1;
    font-family: "Jua",sans-serif;
    font-size: 80px;
    color: $primary;
    span{
      color: #000;
    }
    h2{
      font-size:36px;
      color:$secondary;
    }
  }
  p{
    margin: 30px 0;
    color: $gray-600;
  }
</style>