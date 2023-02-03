<template>
  <div class="navbar">
    <nav>
      <a href="" class="logo">Wyte</a>
      <input type="checkbox" id="check" />
      <div class="main-nav">
        <div class="nav-list">
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink to="/about">About</NuxtLink>
          <NuxtLink to="/festivals">Festivals</NuxtLink>
          <NuxtLink to="/post-list">Posts</NuxtLink>
        </div>
        <div class="login">
          <span class="icon-user"></span>
          <NuxtLink to="#">Login</NuxtLink>
          <!-- <a href="#">Login</a> -->
        </div>
        <label for="check" class="close-menu">
          <span class="icon-cross"></span>
        </label>
      </div>
      <label for="check" class="open-menu">
        <span class="icon-menu"></span>
      </label>
    </nav>
  </div>
</template>
