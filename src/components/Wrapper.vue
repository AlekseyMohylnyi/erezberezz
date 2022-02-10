<template>
  <div class="wrapper">
    <div class="top">
      <img class="top__icon" src="../assets/images/icons/video-camera 1.svg" alt="camera">      
    </div>   
    <Clock /> 
  </div>
</template>

<script>
import Clock from '../components/Clock.vue'
export default {
  name: 'Wrapper',
  components: {
    Clock
  }
}
</script>


<style scoped>
.wrapper {
  margin: 100px auto;
  background-color: var(--background);  
  border-radius: 20px;
  width: 414px;
  height: 896px;
  position: relative;
  overflow: hidden;
  padding-top: 180px;
}

.top {
  position: absolute;
  width: 414px;
  height: 414px;
  left: 0;
  top: -266px;
  background: #2D2D33;  
  border: 5px dashed rgba(69, 71, 86, 0.65);  
  box-shadow: inset 0px -5px #2D2D33; 
  border-radius: 50%;   

  display: flex;
  flex-direction: column;
  justify-content: center;  
  align-items: center; 
}

.top__icon {
  width: 61px;
  margin-top: 14.5rem;
}  

</style>
