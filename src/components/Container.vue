<template>
  <div v-for="(a, i) in insta" :key="i">
    <Post :insta="a"></Post>
  </div>

</template>

<script>
import Post from './Post.vue'

export default {
    
    components : {
        Post,
    },
    props : {
        insta : Array,
    }
}
</script>

<style>

</style>