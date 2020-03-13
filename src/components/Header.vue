<template>
    <div class = "header-content"><h2> {{content}} </h2></div>
  
</template>

<script>

export default {
  name: 'Header',
  props:{
    content: String
  }
  

  }

</script>

<style scoped>
.header-content{
    text-align: center;
  border-bottom: 1px solid black; 
}
</style>