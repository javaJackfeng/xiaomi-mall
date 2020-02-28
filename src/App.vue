<template>
  <div id="app">
    <XiaoMiMall/>
  </div>
</template>

<script>
import XiaoMiMall from './components/XiaoMiMall'
export default {
  name: 'App',
  components:{
    XiaoMiMall
    }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  list-style: none;
}
#app{
  display: absolute;
  width: 100vw;
  height: 100vh;
}
</style>
