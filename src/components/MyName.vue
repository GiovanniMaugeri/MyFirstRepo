<template>

  <h1 v-text='name'>

    </h1>

</template>



<script>
export default {
  name: 'MyName',
  data () {
    return {
      name:'Giovanni Maugeri'
    }
  }
}
</script>



<style scoped>
  h1{
    color: rgb(0,140,0);
  }
</style>
