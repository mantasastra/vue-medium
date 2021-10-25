<template>
  <nav class="navbar navbar-light">
    <div class="container">
      <a class="navbar-brand" href="/">Medium Clone</a>
      <ul class="nav navbar-nav pull-xs-right">
        <li class="nav-item">
          <router-link :to="{ name: 'Home' }" class="nav-link"
            >Home
          </router-link>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">
            <i class="ion-compose"></i>&nbsp;New Post
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">
            <i class="ion-gear-a"></i>&nbsp;Settings
          </a>
        </li>
        <li class="nav-item">
          <router-link :to="{ name: 'Login' }" class="nav-link"
            >Sign In
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar.vue",
};
</script>

<style scoped></style>
