<template>
  <div id="app">
    <bar></bar>
    <router-view class="main"></router-view>
  </div>
</template>

<script>
import bar from './components/bar.vue';
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    bar
  }
}

</script>

<style>
body,html,div,dl,ul,dt,dd,li,p,a,h1,h2,h3,h4,h5,h6{
  text-decoration:none;
  margin:0;
  padding: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
  color: #2c3e50;
  /*margin-top: 60px;*/
}
.main{
  margin-left: 220px;
}
</style>
