<template>
  <li>{{name}} : {{count}}</li>
  <button @click="add">add</button>
</template>
<script>
export default {
  props: {
    name: {
      type: String
    },
    count:{
      type: Number
    },
    add(){
      count += 1;
    }
  }
}
</script>
<style lang="scss">
  
</style>