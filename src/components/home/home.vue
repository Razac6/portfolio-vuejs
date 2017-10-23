<template>
  <div class="hello">
    <section class="home">
      <div class="row-wbd-centered">
        <div class="header">Front End Developer</div>
        <div class="lead">Jan Kowalski</div>
        <mouse-scroll></mouse-scroll>
      </div>
    </section>
     <about></about> 
    <skills></skills>
    <app-footer></app-footer>
  </div>
</template>
<script>
import About from "../about/about.vue";
import Skills from "../skills/skills.vue";
import AppFooter from "../footer/footer.vue";
import MouseScroll from "../share/mouse-scroll/mouse-scroll.vue";
export default {
  components: {
    About,
    Skills,
    AppFooter,
    MouseScroll
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
   .header {
    font-size: 3rem;
  }
  .lead {
    font-size: 2rem;
    opacity: 0.5;
    font-weight: 100;
  }
</style>
