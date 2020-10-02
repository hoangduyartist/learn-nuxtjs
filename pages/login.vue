<template>
  <div class="wrapper-login-form">
    <div class="login-form">
      <div class="title">Create account</div>
      <v-avatar color="indigo" size="56">
        <v-icon dark>
          mdi-account-circle
        </v-icon>
      </v-avatar>
      <v-text-field
        label="User name"
        outlined
      />
      <v-text-field
        label="Password"
        outlined
      />
      <v-btn class="btn-login">LOG IN</v-btn>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.wrapper-login-form {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 100vh;
  box-shadow: 0px 3px 6px #0000004A;
}
.wrapper-login-form > * {
  margin-bottom: 10px;  
}
.login-form {
  min-width: 440px;
  padding: 30px;
  border: 1px solid #41b883;
  border-radius: 6px;
}
.title {
  background-color: #41b883;
  padding: 16px;
  font-size: 20px;
  color: #FFFFFF;
  text-transform: uppercase;
  text-align: center;
  margin-bottom: 30px;
}
.btn-login {
  
  width: 100%;
}
.theme--light.v-btn:not(.v-btn--flat):not(.v-btn--text):not(.v-btn--outlined) {
  padding: 26px 20px;
  background-color: #41b883;
  font-size: 16px;
  color: #FFFFFF;
}
</style>