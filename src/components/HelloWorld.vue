<template>
  <div>
    <h1>{{ msg }}</h1>
    <ul>
      <li><a href="http://www.zachcalvert.com" target="_blank">Zach Calvert</a></li>
      <br>
      <li>Credit for creative commons image <a href="https://commons.wikimedia.org/w/index.php?curid=1453293" target="_blank">here.</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'You have reached a temporarily parked domain.'
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
