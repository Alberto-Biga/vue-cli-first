<template>
  <div>
    <h2>
      La mia prima immagine con Vue CLI!
    </h2>    
    <img src="https://devducks.com/static/devducks/imgs/devducks-by-devrant2.jpg" alt="">
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

</style>