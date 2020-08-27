<template>
  <div clas="inner-block">
  <div class="vue-template">
    <b-form>
      <p class="login-font">Login</p>
      <img :src="image" class="MB-logo" alt="MB-logo">
      <div class="form-group">
        <input type="email" class="form-control form-control-lg" />
      </div>

      <div class="form-group">

        <input type="password" class="form-control form-control-lg" />
      </div>

      <button type="submit" class="btn btn-dark btn-lg btn-block">Login</button>

      <p class="forgot-password text-right mt-2 mb-4">
        <router-link to="/forgot-password">Forgot?</router-link>
      </p>
    </b-form>
    </div>
  </div>
</template>

<script>
export default {
  data  () {
    return {}
  }
}
</script>
