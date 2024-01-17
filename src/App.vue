<script>
import AppHeader from './components/AppHeader.vue';
  // my-component.js
export default {
    data() {
       return { 
        count: 0 
      }
    },
    components:{
      AppHeader
    }
}
</script>

<template>
  <div>
  <AppHeader></AppHeader>
    <h1>maIN</h1>
  </div> 
</template>

<style scoped>
  h1{

    color: red;
  }
</style>
