<template>
    <div id="find_doctor">
        <div class="img">
            <img src="../../../assets/img/illust 1.png">
        </div>

        <div class="text">
            <h2>Bem-vindo!</h2>
            <h3>Insira os dados do profissional</h3>
        </div>

        <div class="form">
            <input type="text" v-model="crm" placeholder="CRM">
            <input type="text" v-model="uf" placeholder="UF">
            <v-btn @click="consultar">Consultar</v-btn>
        </div>
    
    </div>
</template>
  
<script src="./FindDoctor.js" />
  
<style lang="scss" src="./FindDoctor.scss"/>
  