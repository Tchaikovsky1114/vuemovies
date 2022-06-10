<template lang="">
  <router-link to="/" class="logo"><span>Movie</span> FLEX</router-link>
</template>

<style lang="scss" scoped>
@import '../scss/main.scss';
    
  .logo{
    font-family: 'Jua', sans-serif;
    font-size: 20px;
    color: $black;
    text-decoration: none;
    
    span{
      color: $primary;
     
    }
     &:hover{
      color: $black;
    }
  }
  
</style>