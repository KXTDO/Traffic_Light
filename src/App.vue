<template>
  <div id="app">
    <TrafficLight/>
  </div>
</template>

<script>
import TrafficLight from './components/TrafficLight.vue'

export default {
  name: 'App',
  components: {
    TrafficLight
  }
}
</script>

<style>
  #app{
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;    
    }
  body{
    background-color: #9197FA; 
  }
</style>
