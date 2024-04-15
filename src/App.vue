<template>
  <v-app>
    <Login />
  </v-app>
</template>

<script>
import Login from './template/views/login/LoginView.vue'

export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style lang="scss">
#app {
  .v-application--wrap {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
}
</style>
