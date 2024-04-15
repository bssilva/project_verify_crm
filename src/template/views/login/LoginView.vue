<template>
  <div id="login">
    <div class="img">
      <img src="../../../assets/img/illust 1.png">
    </div>

    <div class="text">
      <h2>Bem-vindo!</h2>
      <h3>Por favor, faça login em sua conta existente</h3>
    </div>

    <div class="form">
      <input type="email" v-model="email" placeholder="Email">
      <input type="password" v-model="senha" placeholder="Password">
      <button @click="login">Log In</button>
    </div>

  </div>
</template>

<script>
export default {
  methods: {
    login(){
    }
  }

}
</script>

<style lang="scss">
#login {
  .img {
      display: flex;
      justify-content: center;
      align-items: center;

  }

  .text {
    h2, h3 {
      color: #FFFFFF;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: 'Raleway';
      margin-top: 50px;
    }
    h2{
      font-size: 20px;
      line-height: 23.48px;
      font-weight: 700;
    }
    h3 {
      font-size: 14px;
      line-height: 16.44px;
      font-weight: 400;
    }

  }

  .form {
    input {
      color: #FFFFFF;
      border: 1px solid #FFFFFF;
      border-radius: 15px;
      padding: 10px 20px;
      width: 335px;
      height: 50px;
      cursor: pointer;
      display: flex;
      font-family: 'Raleway';
      margin-top: 20px;
    }
    button {
      background-color: #2BC990;
      color: #FFFFFF;
      font-weight: 700;
      border-radius: 15px;
      width: 335px;
      height: 50px;
      margin-top: 20px;
      font-family: 'Raleway';
    }
  }
}
</style>