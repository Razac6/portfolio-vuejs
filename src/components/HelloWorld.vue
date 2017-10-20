<template>
  <div class="hello">
    <section class="home">
      {{msg}}
    </section>
  </div>
</template>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to webbd portfolio'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

section.home{
  width: 100%;
  max-height: 100vh;
  background-color: #000000;
}

</style>
