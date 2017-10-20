<template>
  <div class="hello">
    <section class="home"></section>
     <about></about> 
    <section class="skills"></section>
    <section class="footer"></section>

  </div>
</template>
<script>
import About from './About.vue';
export default {
  components: {
    About
  },
  name: "Home"
};
</script>
<style lang="scss" scoped>
section {
  &.home {
    background-color: #efcb7b;
  }
  &.skills {
    background-color: #ece7de;
  }

  &.footer {
    background-color: #7115d8;
    height: 200px;
  }
  width: 100%;
  height: 100vh;
  color: #fff;
}
</style>
