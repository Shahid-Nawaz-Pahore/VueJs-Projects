<template>
    <div id="i">
        <h1>This is interpulation and data Component </h1>
        <h2>2+2 are equal to  {{ 2+2 }}</h2>

    </div>
</template>

<script>
export default {
    name:"IntepolationAndData",
}
</script>
<style scoped>
#i{
    background-color: aqua;
    font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: green;
  margin-top: 1px;
}
h1{
    text-align: center;
    color: blue;
}
</style>