<template>
  <div>
    Thanksページ
    <HeadComp></HeadComp>
    送信ありがとうございました!
  </div>
</template>

<script>
import HeadComp from '@/components/modules/HeadComp'
import { mapActions, mapGetters } from 'vuex'

export default {
  name: 'thanks',
  components: {
    HeadComp
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
