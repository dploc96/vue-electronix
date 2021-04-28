<template>
  <TopBar/>
  <Header/>
</template>

<script>
import TopBar from './components/TopBar.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    TopBar,
    Header
  }
}
</script>

<style>
body {
  background:url(/images/bg.jpg) no-repeat #fff center top;
  padding:0;
  font-family:Arial, Helvetica, sans-serif;
  font-size:11px;
  margin:0px auto auto auto;
  color:#000;
}

p{
  padding:2px;
  margin:0px;
}

#app {
  width:1000px;
  height:auto;
  margin:auto;
  padding:0px;
}
</style>
