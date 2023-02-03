<template>
  <div class="table-container">
    <div class="table-text">
      <h2>User List</h2>
    </div>
    <div class="comment-search">
      <div class="search-bar">
        <div class="icon">
          <span class="icon-search"></span>
        </div>
        <input type="text" class="input" placeholder="Search" />
      </div>
    </div>
    <div class="table">
      <table class="table-data">
        <thead>
          <tr>
            <th>ID</th>
            <th>Name</th>
            <th>Email</th>
            <th>Gender</th>
            <th>Status</th>
            <th>Manage</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="user in userlist">
            <td>{{ user.id }}</td>
            <td>{{ user.name }}</td>
            <td>{{ user.email }}</td>
            <td>{{ user.gender }}</td>
            <td>{{ user.status }}</td>
            <td>Edit</td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="comment-container">
      <div class="comment-text">
        <h2>Comments</h2>
      </div>
      <div class="comment-search">
        <div class="search-bar">
          <div class="icon">
            <span class="icon-search"></span>
          </div>
          <input type="text" class="input" placeholder="Search" />
        </div>
      </div>
      <div class="comments" v-for="com in commentlist">
        <img src="../assets/coffee.png" />
        <div class="comment-user">
          <h2>{{ com.name }}</h2>
          <h3>{{ com.email }}</h3>
          <p>{{ com.body }}</p>
          <div class="ids">
            <p>ID: {{ com.id }}</p>
            <p>Post ID: {{ com.post_id }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
const { data: userlist } = await useFetch(
  'https://gorest.co.in/public/v2/users'
);
const { data: commentlist } = await useFetch(
  'https://gorest.co.in/public/v2/comments'
);
</script>
