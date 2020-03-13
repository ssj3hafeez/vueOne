<template>
    <div class = "compC-content"><h2> {{content}} </h2></div>
  
</template>

<script>

export default {
  name: 'CompC',
  props:{
    contentC: String
  }
  

  }

</script>

<style scoped>
.compB-content{
    text-align: center;
  border-bottom: 1px solid black; 
}
</style>