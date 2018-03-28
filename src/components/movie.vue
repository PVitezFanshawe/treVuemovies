<template>
    <h1>{{ moviesroute }} {{$route.params.id}} </h1>
</template>
<script>

export default {
  name: 'movie' ,
  data() {
      return {
          moviesroute : "this is the movie route for",
      }
  }
}
</script>
<style>

</style>
