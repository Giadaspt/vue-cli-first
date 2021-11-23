<template>
  <header>
      <h2>E tu come le preferisci le uova?</h2>
    <ul>
      <li> <a href="#"> {{eggs[0].uova}} </a> </li>
      <li> <a href="#"> {{eggs[1].uova}} </a> </li>
      <li> <a href="#"> {{eggs[2].uova}} </a> </li>
      <li> <a href="#"> {{eggs[3].uova}} </a> </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "Header",

  data() {
    return  {
      eggs: [
        {uova: "Sode"},
        {uova: "Alla coque"}, 
        {uova: "in camicia"},
        {uova: "Strapazzate"},
      ]
    }
  }

}
</script>

<style scoped>
  header {
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: white;
    background-color: #265372;
  }

  ul li {
    display: inline-block;
    list-style: none;
  }

  ul li a {
    color: white;
    text-decoration: none;
    padding-right: 16px;
  }

  h2 {
    padding-left: 32px;
  }

</style>