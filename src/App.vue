<template>
  <div id="app">
    <my-header></my-header>
    <router-view></router-view>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader'
import MyHome from './components/MyHome'
export default {
  name: 'App',
  components:{
    'my-header':MyHeader,
  }
}
</script>

<style>

</style>
