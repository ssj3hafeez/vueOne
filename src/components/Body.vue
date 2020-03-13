<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
 
 <compA contentA="COMPONENTA"/>

  <compB contentB="COMPONENTB"/>


  <compC contentC="COMPONENTC"/>

    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    
  
  </div>
</template>

<script>

import compA from './compA.vue'
import compB from './compB.vue'
import compC from './compC.vue'


export default {
  name: 'Body',
  components: {
  compA,
  compB,
  compC
 
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
