<template>
  <footer>
    <div class="container">
      <router-link class="logo-font" to="/">Medium Clone</router-link>
      <span class="attribution"> A Real World Vue project </span>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
footer {
  background: #373a3c;
  margin-top: 3rem;
  padding: 1rem 0;
  position: absolute;
  bottom: 0;
  width: 100%;
}

footer .logo-font {
  vertical-align: middle;
}

footer .attribution {
  vertical-align: middle;
  margin-left: 10px;
  font-size: 0.9rem;
  color: #fff;
  font-weight: 300;
}
</style>
