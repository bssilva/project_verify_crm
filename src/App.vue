<template>
  <v-app>
    <!-- <Login />-->
    <!--<FindDoctor /> -->
    <InfoDoctor />
  </v-app>
</template>

<script>
// import Login from './template/views/login/LoginView.vue'
// import FindDoctor from './template/views/find_doctor/FindDoctor.vue'
import InfoDoctor from './template/views/info_doctor/InfoDoctor.vue'

export default {
  name: 'App',
  components: {
    // Login
    // FindDoctor
    InfoDoctor
  }
}
</script>

<style lang="scss">
@font-face {
  font-family: 'Raleway';
  src: url('~@/assets/fonts/Raleway-VariableFont_wght.ttf')
}

#app {
  .v-application--wrap {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #0A0171;
  }
}
</style>
