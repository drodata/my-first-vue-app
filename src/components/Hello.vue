<template>
  <div class="hello">
    <h1>{{ msg | capitalize }}</h1>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Hello Vux'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #42b983;
}
</style>
