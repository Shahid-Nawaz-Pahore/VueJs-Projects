<template>
    <div id="i">
        <h1>This is interpulation and data Component </h1>
        <h2>2+2 are equal to  {{ 2+2 }}</h2>
        <h2>total lenght of hello is {{ "hello".length }}</h2>
        <h5>My name is {{ name }} and email is {{ email }} and age is {{ Age }}</h5>
        <h1>getfunction  : {{ getData() }}</h1>
        <h1>pass parameter to function return : {{ getParameter("Parameter Pass to function") }}</h1>
    
    </div>
</template>

<script >







export default( {
    name:"IntepolationAndData",
    data() {
        return {
            name:"shahid Nawaz",
            email:"shahidnawaz.edu.pk@gmail.com",
            Age:"22",
            getData:function()
            {
                return "function return data";
            },
            getParameter:function(a)
            {
                return a;
            }
        };
    }
})
</script>
<style scoped>
#i{
    background-color: aqua;
    font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:darkgreen;
  margin-top: 1px;
}

</style>