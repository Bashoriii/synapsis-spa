<template>
  <div class="event-text">
    <h2>Related Event</h2>
    <p>Catch up the upcoming music festival</p>
  </div>
  <div class="container-event">
    <div class="event-card">
      <div class="event-img">
        <img src="../assets/dwp.png" />
      </div>
      <div class="title-text">
        <h2>Djakarta Warehouse Project</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
          adipisci consequatur! Ut sequi eum earum quaerat magni rem dicta!
        </p>
      </div>
      <div class="booknow">
        <NuxtLink to="/blog-detail">Book Now</NuxtLink>
        <NuxtLink to="/blog-detail">
          <span class="icon-circle-right"></span>
        </NuxtLink>
      </div>
    </div>
    <div class="event-card">
      <div class="event-img">
        <img src="../assets/javajazz.png" />
      </div>
      <div class="title-text">
        <h2>Java Jazz Festival</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
          adipisci consequatur! Ut sequi eum earum quaerat magni rem dicta!
        </p>
      </div>
      <div class="booknow">
        <NuxtLink to="/blog-detail">Book Now</NuxtLink>
        <NuxtLink to="/blog-detail">
          <span class="icon-circle-right"></span>
        </NuxtLink>
      </div>
    </div>
    <div class="event-card">
      <div class="event-img">
        <img src="../assets/headincloud.png" />
      </div>
      <div class="title-text">
        <h2>Head in the Cloud</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
          adipisci consequatur! Ut sequi eum earum quaerat magni rem dicta!
        </p>
      </div>
      <div class="booknow">
        <NuxtLink to="/blog-detail">Book Now</NuxtLink>
        <NuxtLink to="/blog-detail">
          <span class="icon-circle-right"></span>
        </NuxtLink>
      </div>
    </div>
    <div class="event-card">
      <div class="event-img">
        <img src="../assets/dwp.png" />
      </div>
      <div class="title-text">
        <h2>Djakarta Warehouse Project</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
          adipisci consequatur! Ut sequi eum earum quaerat magni rem dicta!
        </p>
      </div>
      <div class="booknow">
        <NuxtLink to="/blog-detail">Book Now</NuxtLink>
        <NuxtLink to="/blog-detail">
          <span class="icon-circle-right"></span>
        </NuxtLink>
      </div>
    </div>
    <div class="event-card">
      <div class="event-img">
        <img src="../assets/javajazz.png" />
      </div>
      <div class="title-text">
        <h2>Java Jazz Jakarta</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
          adipisci consequatur! Ut sequi eum earum quaerat magni rem dicta!
        </p>
      </div>
      <div class="booknow">
        <NuxtLink to="/blog-detail">Book Now</NuxtLink>
        <NuxtLink to="/blog-detail">
          <span class="icon-circle-right"></span>
        </NuxtLink>
      </div>
    </div>
    <div class="event-card">
      <div class="event-img">
        <img src="../assets/headincloud.png" />
      </div>
      <div class="title-text">
        <h2>Head in the Cloud</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis sequi
          adipisci consequatur! Ut sequi eum earum quaerat magni rem dicta!
        </p>
      </div>
      <div class="booknow">
        <NuxtLink to="/blog-detail">Book Now</NuxtLink>
        <NuxtLink to="/blog-detail">
          <span class="icon-circle-right"></span>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<!-- --------------------------------------------------------------- -->

<!-- LOOPING TITLE FOR POST LIST -->
<!-- <div class="event-card" v-for="blog in bloglist">
      <div class="event-img">
        <img src="../assets/javajazz.png" />
      </div>
      <div class="title-text">
        <NuxtLink to="#">{{ blog.title }}</NuxtLink>
      </div>
      <div class="booknow">
        <NuxtLink to="/blog-detail">Book Now</NuxtLink>
        <NuxtLink to="/blog-detail">
          <span class="icon-circle-right"></span>
        </NuxtLink>
      </div>
    </div>
  </div>
<script setup>
const { data: bloglist } = await useFetch(
  'https://gorest.co.in/public/v2/posts'
);
</script> -->
