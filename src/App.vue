<template>
  <div id="app">
    <nav class="navbar">
      <div class="container">
        <div class="navbar-header">
        <div class="form-group has-success has-feedback">
          <input type="search" class="form-control" id="search" aria-describedby="searchStatus" placeholder="沙县小吃">
          <span class="glyphicon glyphicon-search form-control-feedback" aria-hidden="true"></span>
          <span id="searchStatus" class="sr-only">(success)</span>
        </div>
          
        </div>
        <div id="navbar" class="collapse navbar-collapse navbar-right">
          <ul class="nav navbar-nav">
            <li><router-link to="/">主页</router-link></li>
            <li><router-link to="/foo">百家餐饮</router-link></li>
            <li><router-link to="/huang">黄焖鸡</router-link></li>         
          </ul>
        </div>
      </div>
    </nav>
    <div class="container">
      <img src="./assets/主图标.png">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img{
  margin-left:0px;
  margin-top: 0;
  float: left;
}
</style>
