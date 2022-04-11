<template>
  <div>
    <h2>
      La mia prima immagine con Vue CLI!
    </h2>    
    <div class="hero">
      <!-- <img src="https://devducks.com/static/devducks/imgs/devducks-by-devrant2.jpg" alt=""> -->
    </div>    
  </div>
</template>

<script>
export default {
  name: 'FirstHero',
  props: {
    msg: String
  }
}
</script>


<style scoped lang="scss">
  .hero{    
    background-image: url("https://devducks.com/static/devducks/imgs/devducks-by-devrant2.jpg");
    background-repeat: no-repeat;
    background-position: center ;
    background-size: cover;
    height: 700px;
  }
</style>