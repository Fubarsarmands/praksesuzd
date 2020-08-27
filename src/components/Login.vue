<template>
  <div class="inner-block">
    <b-form>
      <div class="row justify-content-between">
        <b-col >
          <p class="login-font">Login</p>
            <hr class="underline">
        </b-col>
           <b-col>
            <img :src="logo" class="Magebit-logo" alt="Magebit-logo">
           </b-col>
      </div>

      <div class="  form-group">
        <label class="labelhelp label"> Email</label>
        <input type="text" class="  input form-control form-control-lg " />
        <img :src="mail" class="fa icons1 " alt="icons1">
      </div>

      <div class=" position-relative form-group">
        <label class="labelhelp label">Password</label>
        <input type="text" class=" input form-control form-control-lg" />
      </div>
      <div class="row justify-content-between" style="margin-top: 30px;">
        <div class="col-4">
          <b-button pill variant="orange" size="lg" type="submit">LOGIN</b-button>
        </div>
        <div class="col-4">
          <b-button variant="link ColorGrey" type="button">Forgot?</b-button>
        </div>
      </div>
    </b-form>
  </div>
</template>

<script>
export default {
  data  () {
    return {
      logo: require('@/assets/icons/logo.jpg'),
      mail: require('@/assets/icons/ic_mail.jpg'),
      mailactive: require('@/assets/icons/ic_mail_active.jpg'),
      lock: require('@/assets/icons/ic_lock.jpg'),
      activelock: require('@/assets/icons/ic_lock_active.jpg')
    }
  }
}
</script>
