<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      FOR KNOWING MORE ABOUT PROGRAMMING,<br />
      CHECK OUT
      <a href="https://codersden.hashnode.dev/" target="_blank" rel="noopener"
        >MY BLOGS</a
      >.
    </p>
    <h3>Social Media Profiles</h3>
    <ul>
      <li>
        <a href="https://twitter.com/codeer489" target="_blank" rel="noopener"
          >TWITTER</a
        >
      </li>
      <li>
        <a href="https://www.linkedin.com/in/hardik-undefined-b69533254/" target="_blank" rel="noopener"
          >LINKDIN</a
        >
      </li>
      <li>
        <a href="https://hashnode.com/@unknown619" target="_blank" rel="noopener"
          >HASHNODE</a
        >
      </li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li>
        <a
          href="https://github.com/unknown6191"
          target="_blank"
          rel="noopener"
          >GITHUB</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
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
