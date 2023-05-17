<script>
  import Ciao from './components/Ciao.vue';
  import Jumbo from './components/Jumbo.vue';

  
  export default{

    components: {
      Ciao,
      Jumbo,
    },
  };

</script>


<template>
  <div>
    <Ciao />
    <Jumbo />

  </div>
</template>


<style scoped>
  div{
    width: 400px;
    margin: auto;
  }
  
</style>