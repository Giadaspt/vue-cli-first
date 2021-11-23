<template>
  <h1> {{titolo}} </h1>
</template>

<script>
export default {
  name: "Title",

  data() {
    return {
      titolo: "La mia prima app con Vue CLI!"
    }
  },
}
</script>

<style scoped>
  h1 {
    color: rgb(255, 234, 49);
    background-color: rgb(110, 163, 133);
    padding: 8px;
  }
</style>