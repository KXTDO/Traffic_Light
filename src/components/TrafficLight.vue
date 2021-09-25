<template>
  <div class="container">
    <div class="circle red"></div>
    <div class="circle yellow"></div>
    <div class="circle green"></div>
  </div>
</template>

<script>
export default {
  name: 'TrafficLight',
  
}
</script>


<style scoped>
  .container {
    background-color: #2c3e50;
    border-radius: 80px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-direction: column;
    padding: 30px;
    height: 400px;
    width: 100px;
  }

  .circle {
    background-color: rgba(0, 0, 0, 0.3);
    border-radius: 50%;
    position: relative;
    height: 100px;
    width: 100px;
  }

  .circle.red {
    background-color: #c0392b;
    box-shadow: 0 0 30px 10px #c0392b;
  }

  .circle.yellow {
    background-color: #f1c40f;
    box-shadow: 0 0 30px 10px #f1c40f;
  }

  .circle.green {
    background-color: #2ecc71;
    box-shadow: 0 0 30px 10px #2ecc71;
  }
</style>
