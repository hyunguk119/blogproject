<template>
  <div>
    <div>
      <h4>상세페이지</h4>
      <h5>{{ blog[$route.params.id].title }}</h5>
      <p>{{ blog[$route.params.id].content }}</p>
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  props : {
    blog : Array,
  }
}
</script>

<style>

</style>