<template lang="">
  <header>
    <Logo />
    <div class="nav nav-pills">
      <div v-for="nav in navigations"
      class="nav-item"
      :key="nav.name">
        <router-link :to="nav.href" class="nav-link" active-class="active">
          {{nav.name}}
        </router-link>
      </div>
    </div>
  </header>
</template>
<script>
import Logo from './Logo.vue'
export default {
  components:{
    Logo
  },
  data() {
    return {
      navigations: [
        {
          name: 'Search',
          href: '/',
        },
        {
          name: 'Movie',
          href: '/movie',
        },
        {
          name: 'About',
          href: '/about',
        },
      ]
    }
  }
}
</script>
<style lang="scss" scoped>
  header{
    height: 70px;
    padding: 0 40px;
    display:flex;
    align-items: center;
    .logo{
      margin-right: 40px;
    }
  }
</style>