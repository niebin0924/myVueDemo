

<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <h2>About Us</h2>
    <about-one></about-one>

  </div>
</template>

<script>
  import AboutOne from './about_one.vue'
  export default {
    name: 'about',
    data () {
      return {
        msg: '关于我们'
      }
    },
    components: {
      AboutOne
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
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
</style>
