<template>
  <p>{{string}}</p>
</template>

<script>
export default {
  name: 'stringComp',
  data () {
    return {
      string: '入力された感想をここに出す'
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
