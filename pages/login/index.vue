<template>
  <div class="hero is-fullheight">
    <div class="hero-body p-t-0">
      <div class="container has-text-centered">
        <div class="column is-8 is-offset-2">
          <h3 class="title">Login</h3>
          <hr class="login-hr">
          <p class="subtitle ">Please login to see our cool stuff!</p>
          <div class="box">
            <div class="box">
              <img src="https://miro.medium.com/proxy/0*4fHRBbNhF_1jpdCM.jpeg">
            </div>
            <div class="title has-text-grey is-5">Please enter your email and password.</div>
          </div>
          <form>
            <div class="field">
              <div class="control">
                <input
                  class="input is-large"
                  type="email"
                  placeholder="Email"
                  autofocus=""
                >
              </div>
            </div>
            <div class="field">
              <div class="control">
                <input
                  class="input is-large"
                  type="password"
                  placeholder="Password"
                >
              </div>
            </div>
          </form>
          <label
            class="checkbox"
            style="margin: 20px;"
          >
            <input type="checkbox">
            Remember me
          </label>
          <button class="button is-block is-danger is-large is-fullwidth">Login</button>
          <p class="has-text-grey">
            <a href="">Sign Up</a> &nbsp;·&nbsp;
            <a href="">Forgot Password</a> &nbsp;·&nbsp;
            <a href="">Need Help?</a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.p-t-0 {
  padding-top: 0px;
}
</style>