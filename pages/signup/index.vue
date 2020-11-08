<template>
  <div class='container'>
    <div class="field">
      <label class="label">Name</label>
      <div class="control">
        <input
          class="input"
          type="text"
          placeholder="Text input"
        >
      </div>
    </div>

    <div class="field">
      <label class="label">Username</label>
      <div class="control has-icons-left has-icons-right">
        <input
          class="input is-success"
          type="text"
          placeholder="Text input"
          value="bulma"
        >
        <span class="icon is-small is-left">
          <i class="fas fa-user"></i>
        </span>
        <span class="icon is-small is-right">
          <i class="fas fa-check"></i>
        </span>
      </div>
      <p class="help is-success">This username is available</p>
    </div>

    <div class="field">
      <label class="label">Email</label>
      <div class="control has-icons-left has-icons-right">
        <input
          class="input is-danger"
          type="email"
          placeholder="Email input"
          value="hello@"
        >
        <span class="icon is-small is-left">
          <i class="fas fa-envelope"></i>
        </span>
        <span class="icon is-small is-right">
          <i class="fas fa-exclamation-triangle"></i>
        </span>
      </div>
      <p class="help is-danger">This email is invalid</p>
    </div>

    <!-- <div class="field">
      <label class="label">Subject</label>
      <div class="control">
        <div class="select">
          <select>
            <option>Select dropdown</option>
            <option>With options</option>
          </select>
        </div>
      </div>
    </div> -->

    <div class="field">
      <div class="control">
        <label class="checkbox">
          <input type="checkbox">
          I agree to the <a href="#">terms and conditions</a>
        </label>
      </div>
    </div>

    <div class="field">
      <div class="control">
        <label class="radio">
          <input
            type="radio"
            name="question"
          >
          Male
        </label>
        <label class="radio">
          <input
            type="radio"
            name="question"
          >
          Female
        </label>
      </div>
    </div>

    <div class="field is-grouped">
      <div class="control">
        <button class="button is-link">Submit</button>
      </div>
      <div class="control">
        <button class="button is-link is-light">Cancel</button>
      </div>
    </div>
    <div class="separator">
      <hr class="f-1">
      <p class="m-v-5">or</p>
      <hr class="f-1">
    </div>
    <div class="field is-grouped">
      <div class="control">
        <button class="button is-link is-white">Google</button>
      </div>
      <div class="control">
        <button class="button is-link is-light">Facebook</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.separator {
  display: flex;
  flex-direction: row;
  align-items: center;
}

hr {
  border: 1px solid green;
}

.m-v-5 {
  margin: 0px 5px;
}

.f-1 {
  flex: 1;
}
</style>