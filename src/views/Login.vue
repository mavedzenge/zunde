<template>
  <div class="container-fluid">
    <div class="back pb-3">
      <a href="#"><span class="pl-2" ><b-icon icon="chevron-left"></b-icon>Go back</span></a>
    </div>
    <div class="v2_40">
      <div class="container">
        <div class="logo">
          <img src="../assets/v2_39.png" alt="Zunde Logo">
        </div>
        <p class="text py-3">Log in to your Zunde account to see your mortgage application progress and dashboard.</p>
        <div class="py-2">
          <b-form-input class="input py-3" v-model="email"  type="email" placeholder="Email"></b-form-input>
        </div>
        <div class="py-2">
          <b-form-input class="input py-3" v-model="text" type="password" placeholder="Password"></b-form-input>
        </div>
        <div class="py-2">
          <b-form-input class="input py-3" v-model="text"  type="password" placeholder="Password"></b-form-input>
        </div>
        <div class="pb-2">
          <b-button class="w-100 py-2" variant="primary">Login</b-button>
        </div>
        <a class="forgot" href="#">Forgot Password?</a>
        <p class="signup">Don't have an account? <a href="#"> Sign up</a></p>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Login',
  components: {
  }
}
</script>

<style scoped>
.v2_40 {
  width: 604px;
  height: 548px;
  background: rgba(255,255,255,1);
  opacity: 1;
  position: relative;
  margin: auto;
  border-top-left-radius: 8px;
  border-top-right-radius: 8px;
  border-bottom-left-radius: 8px;
  border-bottom-right-radius: 8px;
  box-shadow: 1px 1px 30px rgba(0, 0, 0, 0.15000000596046448);
  overflow: hidden;
}
.container {
  width: 350px;
}
.logo {
  padding-top: 80px;
}
.logo img {
    width: 149px;
    height: 35px;
    opacity: 1;
}
p.text {
    color: rgba(137,134,136,1);
    position: relative;
    margin: auto;
    font-family: Mulish;
    font-weight: Bold;
    font-size: 14px;
    opacity: 1;
    text-align: center;
}
.input {
  margin: auto;
}
.signup, .forgot {
    font-family: Mulish;
    font-weight: Bold;
    font-size: 15px;
    text-decoration: none;
    padding-top: 5px;
}
.back {
    color: rgba(137,134,136,1);
    top: 0px;
    left: 13px;
    font-family: Mulish;
    font-weight: Bold;
    font-size: 15px;
    opacity: 1;
    text-align: left;
}
.back a {
  text-decoration: none;
  color: rgba(137,134,136,1);;
}
</style>
