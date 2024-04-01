<template>
  <div>
    <AppHeader />
    <ItemList :items="items" />
  </div>
</template>

<script>
export default {
  name: 'AppHome',
  components: {
    AppHeader,
    ItemList,
  },
  data(){
    return{
    },
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
