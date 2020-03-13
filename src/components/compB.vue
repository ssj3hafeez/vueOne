<template>
    <div class = "compB-content"><h2> {{content}} </h2></div>
  
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