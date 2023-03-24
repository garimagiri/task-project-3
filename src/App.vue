<template>
  <div class="container">
    <PageOne/>
    
  </div>
  
</template>

<script>
import PageOne from './components/PageOne.vue'

export default {
  name: 'App',
  components: {
    PageOne,
  }
}
</script>

<style>
@import './assets/App.css';
</style>
