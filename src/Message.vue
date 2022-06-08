<template lang="">
  <div>
    <h3>{{msg}}</h3>
    <button @click="add">asd</button>
  </div>
  
</template>
<script>
export default {
  data(){
    return {
      msg: ''
    }
  },
  methods: {
    add() {
      this.msg += '1'
    }
  }
}
</script>
<style lang="">
  
</style>