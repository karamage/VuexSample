<template>
  <h1>{{title}}</h1>
</template>

<script>
export default {
  name: 'headComp',
  data () {
    return {
      title: '感想を入力'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
