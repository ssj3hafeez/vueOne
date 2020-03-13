<template>
    <div class = "compA-content"><h2>Component A</h2></div>

</template>

<script>

export default {
  name: 'CompA',
  props:{
    contentA: String
  }
  

  }

</script>

<style scoped>
.compA-content{
    text-align: center;
  border-bottom: 1px solid black; 
}
</style>