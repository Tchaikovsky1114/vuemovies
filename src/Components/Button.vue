<template lang="">
  <div
  v-bind="$attrs"
  class="btn"
  @click="hello">
    <slot></slot>
  </div>
</template>
<script>
import { onMounted } from '@vue/runtime-core';
export default {
  inheritAttrs: false,
  props:{
    color: {
      type: String,
      default: 'gray'
    }
  },
  // 부모컴포넌트에서 사용할 메서드 정의
  emits:['hello'],
  setup(props,context){
    function hello(){
      context.emit('hello')
}
    // onMounted(()=> {
    //   console.log(props.color)
    //   console.log(context.attrs)
    // })
    return hello
  }
}
</script>
<style lang="">
  
</style>