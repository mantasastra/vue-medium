<template>
  <div class="auth-page">
    <div class="container page">
      <div class="row">
        <div class="col-md-6 offset-md-3 col-xs-12">
          <h1 class="text-xs-center">Sign Up</h1>
          <p class="text-xs-center">
            <router-link to="/login">Have an account?</router-link>
          </p>

          <ul class="error-message">
            <li style="list-style: none">
              This email address is already used.
            </li>
          </ul>

          <form>
            <fieldset class="form-group">
              <input
                class="form-control form-control-lg"
                placeholder="Name"
                type="text"
              />
            </fieldset>
            <fieldset class="form-group">
              <input
                class="form-control form-control-lg"
                placeholder="Email Address"
                type="text"
              />
            </fieldset>
            <fieldset class="form-group">
              <input
                class="form-control form-control-lg"
                placeholder="Password"
                type="password"
              />
            </fieldset>

            <button class="btn btn-lg btn-secondary pull-xs-right">
              Sign up
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Register",
};
</script>

<style scoped></style>
