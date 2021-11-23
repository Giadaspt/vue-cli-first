<template>
  <footer>
    <h3>{{buone}}</h3>
  </footer>
</template>

<script>
export default {
 name: "Footer",

 data(){
   return {
     buone: "Buone in tutte le salse!"
   }
 }
}
</script>

<style scoped>
  
  footer {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 80px;
    background-color: seagreen;
  }

  h3 {
    font-size: 40px;
    color: rgb(210, 255, 88);
  }
</style>