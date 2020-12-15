<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide on how to configure exploring life <br>
      <!-- <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>. -->
    </p>
    <!-- <h3>Installed CLI Plugins</h3> -->
    <!-- <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul> -->
    <h3>Have a visit</h3>
    <ul>
      <li><a href="https://www.bemytravelmuse.com/how-to-make-money-with-travel-blog/" target="_blank" rel="noopener">Travelling</a></li>
      <li><a href="https://blogs.nasa.gov/" target="_blank" rel="noopener">Space</a></li>
      <li><a href="https://traveltriangle.com/blog/waterfalls/" target="_blank" rel="noopener">Waterfalls</a></li>
      <li><a href="http://marinebioblog.blogspot.com/" target="_blank" rel="noopener">cars</a></li>
      <li><a href="http://marinebioblog.blogspot.com/" target="_blank" rel="noopener">Ocean</a></li>
    </ul>
    <!-- <h3>Details</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">Admin</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">Contact</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">Address</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loa</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
