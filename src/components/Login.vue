<template>
  <div clas="inner-block">
  <div class="vue-template">
    <b-container class="bv-example-row">
      <b-row>
          <p class="login-font">Login</p>
        <b-col>
          <img :src="logo" class="Magebit-logo" alt="Magebit-logo">
        </b-col>
      </b-row>
    </b-container>

      <div class="form-group">
        <input type="email" class="form-control form-control-lg" />
      </div>

      <div class="form-group">

        <input type="password" class="form-control form-control-lg" />
      </div>
  </div>
    <div class="row justify-content-between" style="margin-top: 30px;">
      <div class="col-4">
        <b-button pill variant="orange" size="lg" type="submit">LOGIN</b-button>
      </div>
      <div class="col-4">
        <b-button variant="link ColorGrey" type="button">Forgot?</b-button>
      </div>
      </div>
    </div>
</template>

<script>
export default {
  data  () {
    return {
      logo: require('@/assets/icons/logo.jpg')
    }
  }
}
</script>
