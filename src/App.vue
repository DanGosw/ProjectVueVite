<script setup>
  // import ButtonCount from './components/ButtonCount.vue'
  import BlogPost from './components/BlogPost.vue'
</script>

<template>
  <h1>
    Hello World
  </h1>

  <!-- <ButtonCount/> -->

  <BlogPost title="AnonimeUser007" content="Hello new user, How are you?" color-text="primary"/>
  <BlogPost title="RobotAssasin" content="Hi, I am fine, and you" color-text="danger"/>
  
</template>

<style>

body{
    background-color: rgb(55, 63, 75);
    padding: 3em;
}

</style>
