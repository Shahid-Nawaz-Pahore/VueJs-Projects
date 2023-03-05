<script stutup>


export default( {
    name:"MethodDefineUse",

    data(){
        return{
           count:0,
           count1:0,
           count2:0,
        }
    },
   methods:{
    ADD(){this.count = this.count + 1},
    ADD1(){this.count1 = this.count1 + 1},

    SUB(){this.count = this.count - 1},
    SUB1(){this.count1 = this.count1 - 1},


    
  }
})
</script>




<template>
  <div id="m">
    <h1>Count app using option api </h1>
    <div class="bi">
     <h1>
      <button @click="ADD()">+</button>
      {{ count }}
    <button @click="SUB()">-</button>
  </h1>
    </div>
     <div class="b2">
      <h1>
      <button @click="ADD1()">+</button>
      {{ count1 }}
    <button @click="SUB1()">-</button>
  </h1>
     </div>
     
   <h1> {{ count2=count+count1 }}</h1>
       
  </div>
</template>
<style scoped>
#m{
    background-color:beige;
    font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:darkgreen;
  margin-top: 1px;
}

</style> 