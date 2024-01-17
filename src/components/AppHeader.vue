<script>
  // my-component.js
export default {
    data() {
       return { 
        title : 'hello world' 
      }
    },
}
</script>

<template>
  <h1>
    {{ title }}
  </h1>
</template>

<style scoped>
  h3{
    color: blue;
  }
</style>
