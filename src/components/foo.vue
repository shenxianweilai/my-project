<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <span v-once>长期关注:{{msg}}</span>
    <input v-model="msg" placeholder="edit me">
    <div v-bind:id="'list-'+id"></div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: '粮油店'
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
