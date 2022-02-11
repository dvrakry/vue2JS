<template>
  <div>
    <p>{{$route.params.id}}</p>
    <h4>Detail 화면</h4>
    <h5>{{블로그글[$route.params.id].title}}</h5>
    <p>{{블로그글[$route.params.id].content}}</p>
  </div>
  </template>

<script>
export default {
  name : 'detail',
  props : {
    블로그글 : Array,
  }
}
</script>

<style>

</style>