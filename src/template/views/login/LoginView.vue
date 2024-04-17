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

<script src="./LoginView.js"/>

<style lang="scss" src="./LoginView.scss"/>