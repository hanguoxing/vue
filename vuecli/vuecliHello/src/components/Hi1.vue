<template>
  <div class="hi">
    <h1>{{ msg }}</h1>
    <h2>韩小星星1</h2>
    <h3>{{$route.params.username}}</h3>
    <h3>{{$route.params.id}}</h3>
  </div>
</template>

<script>
export default {
  name: 'hi',
  data () {
    return {
      msg: '我是子页面一'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
