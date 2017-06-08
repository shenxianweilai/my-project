<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>重点关注</h2>
    <ul>
      <li><a href="https://vuejs.org" target="_blank">微信公众号</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">微博</a></li>
      <li><a href="https://gitter.im/vuejs/vue" target="_blank">github</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">我的南京</a></li>
      <br>
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">更多相关内容后续跟上</a></li>
    </ul>
    <h2>热门餐饮</h2>
    <ul>
      <li><a href="http://router.vuejs.org/" target="_blank">土菜馆</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">食堂</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">蛋糕店</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">油炸小吃</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: '让美菜BD轻松做好苦闷单调的工作'
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
