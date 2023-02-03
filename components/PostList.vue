<template>
  <div class="blog-text">
    <h2>Latest Posts</h2>
  </div>
  <div class="container-event">
    <div class="event-card" v-for="blog in bloglist">
      <div class="blog-img">
        <img src="../assets/post-img.jpg" />
      </div>
      <div class="blogs">
        <NuxtLink to="/reviews" class="blog-title">{{ blog.title }}</NuxtLink>
      </div>
      <div class="content">
        <p>{{ blog.body }}</p>
      </div>
      <div class="author">
        <p>{{ blog.id }} | {{ blog.user_id }} | Anonymous</p>
      </div>
    </div>
  </div>
</template>
<script setup>
const { data: bloglist } = await useFetch(
  'https://gorest.co.in/public/v2/posts'
);
</script>
