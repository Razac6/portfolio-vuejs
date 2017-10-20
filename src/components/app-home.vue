<template>
  <div class="hello">
    <section class="home"></section>
     <about></about> 
    <skills></skills>
    <app-footer></app-footer>
  </div>
</template>
<script>

import About from './app-about.vue';
import Skills from './app-skills.vue';
import AppFooter from './app-footer.vue';

export default {
  components: {
    About,
    Skills,
    AppFooter
  },
  name: "app-home"
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
