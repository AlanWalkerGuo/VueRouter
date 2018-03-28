<template>
  <div>
    <h1>{{msg}}</h1>
     <router-view/>
  </div>
 
</template>

<script>
export default {
  name: 'Hi',
  data () {
    return {
      msg: 'Hi,Hi,Hi'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
