<template>
  <div id="app">
    <app-navbar></app-navbar>
     <router-view/>
  </div>
</template>

<script>
import Navbar from './components/Navbar'

export default {
  components: {
    'appNavbar': Navbar,
  },



}
</script>

<style>

</style>
