<template>
    <div class = "footer-content"><h4> Here lies the bottom of the footer </h4></div>
  

</template>

<script>

export default {
  name: 'myFooter',
  props: {
    footer: String 
  }

  }

</script>

<style scoped>
.footer-content{
  border-bottom: 1px solid black; 
}
</style>