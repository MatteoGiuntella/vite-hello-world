<script>
  // my-component.js
export default {
    data() {
       return { 
        title : 'bella li' 
      }
    },
}
</script>

<template>
  <h3>
    {{ title }}
  </h3>
</template>

<style scoped>
  h3{
    color: blue;
  }
</style>
