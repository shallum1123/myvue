<template>
  <div id="app">
   <h1> 甜甜是个白痴吗？</h1></br>
   <h3> 是的</h3>
   <ll></ll>
   <ls></ls>
  </div>
</template>

<script>
import ll from "@/components/HelloWorld.vue"
import ls from "@/components/my.vue"
export default {
  name: 'App',
  components:{
    ll,ls
  }

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
</style>
