<template>
  <header>
      <h2>E tu come le preferisci le uova?</h2>
    <ul>
      <li> <a href="#"> Sode </a> </li>
      <li> <a href="#"> Alla coque </a> </li>
      <li> <a href="#"> In camicia </a> </li>
      <li> <a href="#"> Strapazzate </a> </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style>
  header {
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: white;
    background-color: #265372;
    border-bottom: #a57c48;
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