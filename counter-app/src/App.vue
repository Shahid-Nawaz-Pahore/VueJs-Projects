<script setup>
import { ref } from 'vue';

const count=ref(0);
</script>

<template>
  <main><div>
  
  <button @click="count++">+</button>
  <h1>{{count}}</h1>
  <button  @click="count--">-</button>
  </div></main>
</template>
<style scoped>
main{
  background-color: aqua;
  height: 100vh;
}
div{
  
  text-align: center;
  justify-content: center;
}
button {
  background-color: #4CAF50;
  border: none;
  color: white;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 8px;
  box-shadow: 20px 20px 50px #888888;
  cursor: pointer;
  margin: 20px;
  padding: 20px;
}

</style>

