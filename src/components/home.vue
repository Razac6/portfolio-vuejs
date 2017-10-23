<template>
  <div class="hello">
    <section class="home"></section>
     <about></about> 
    <skills></skills>
    <app-footer></app-footer>
  </div>
</template>
<script>

import About from './about.vue';
import Skills from './skills.vue';
import AppFooter from './footer.vue';

export default {
  components: {
    About,
    Skills,
    AppFooter
  },
  name: "home"
};
</script>
<style lang="scss" scoped>
section {
  &.home {
    background-color: #efcb7b;
  }
  width: 100%;
  height: 100vh;
  color: #fff;
}
</style>
