<template>
  <div>
    <h1>{{ msg }}</h1>
    <ul>
      <li>Domain owned by <a href="http://www.zachcalvert.com" target="_blank">Zach Calvert</a></li>
      <br>
      <br>
      <li>Code available at <a href="https://github.com/ZacharyCalvert/parked" target="_blank">GitHub</a></li>
      <br>
      <li>Deployed to <a href="https://aws.amazon.com/s3" target="_blank">Amazon S3</a></li>
      <br>
      <li>Built with <a href="https://github.com/vuejs/vue-cli" target="_blank">Vue-CLI</a></li>
      <br>
      <li>Credit for creative commons image <a href="https://commons.wikimedia.org/w/index.php?curid=1453293" target="_blank">here.</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Parked',
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
