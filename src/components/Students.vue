<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>Abdullah</li>
      <li>Inam</li>
      <li>Fatima</li>
      <li>Saara</li>
      <li>Zoya</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Student List',
  data () {
    return {
      msg: 'List of students'
    }
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
