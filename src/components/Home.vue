<template>
  <div class="hello">
    <section class="home">
    </section>
        <section class="about">
    </section>
            <section class="skills">
    </section>
  </div>
</template>
<script>
export default {
  name: 'Home'
}
</script>
<style lang="scss" scoped>

section{
  &.home{
    background-color: #efcb7b;
  }
  &.about{
    background-color: #24262d;
  }
  &.skills{
     background-color: #ece7de;
  }
    width: 100%;
     height: 100vh;
     color: #fff;
}
</style>
