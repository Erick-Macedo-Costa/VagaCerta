<template>
  <v-app-bar app flat color="primary">
    <v-img src="@/assets/VagaCerta.png" max-height="120" class="mr-2"></v-img>
    <v-btn text to="/vagas">
      Vagas
    </v-btn>
    <v-btn text to="/empresas">
      Empresas
    </v-btn>
    <v-btn text to="/candidato">
      Candidato
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text icon color="black" variant="flag">
      <v-icon>mdi-account-plus</v-icon>
     <!--TEXTO POREM TA BUGADO-->
     teste
    </v-btn>
    <v-btn text icon color="black" variant="flag">
      <v-icon>mdi-login</v-icon>
      teste
    <!--TEXTO POREM TA BUGADO-->
    </v-btn>
  </v-app-bar>
</template>

<script setup>
//
</script>
