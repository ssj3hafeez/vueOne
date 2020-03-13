<template>
    <div class = "compB-content"><h2> Component B </h2>
  
   <a href="https://vuejs.org/v2/guide/#Getting-Started" > Vue to Kill </a>

</div>
</template>

<script>

export default {
  name: 'CompB',
  props:{
    contentA: String
  }
  

  }

</script>

<style scoped>
.compB-content{
    text-align: center;
  border-bottom: 1px solid black; 
}
</style>