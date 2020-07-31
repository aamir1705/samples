<template>
  <sample-one></sample-one>
</template>

<script>
import SampleOne from './components/sample/Sample.vue'


export default {
  components:{
    'sample-one' : SampleOne
  }


}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
