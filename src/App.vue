<template lang="">
  <Header />
   <RouterView />

</template>
<script>
import Header from './Components/Header.vue'
export default {
  components: {
    Header
  }
}
</script>
<style lang="scss">
  @import "./scss/main.scss";
</style>
