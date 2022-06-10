<template lang="">
  <div class="container">
    <input class="form-control" v-model="title" placeholder="Search for Movies, Series & More" type="text" />
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: '',
    };
  },
};
</script>
<style lang=""></style>
