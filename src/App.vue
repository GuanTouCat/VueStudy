<template>
  <div id="app">
    <LeftNav></LeftNav>

    <div class="main">
      <router-view></router-view>
    </div>
  </div>


</template>

<script>
  import LeftNav from '@/components/common/LeftNav'

export default {
  name: 'App',
  components:{LeftNav}
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
  .main{
    width: 95%;
    height: 100%;
    background-color: #eff2f7;
    float: left;
    overflow: auto;
  }
</style>
