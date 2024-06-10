<template>
  <v-app>
    <!-- Container principal, usando classes de layout do Vuetify para centralizar vertical e horizontalmente -->
    <div class="d-flex justify-center align-center" style="height: 100vh;">
      <!-- Imagem de fundo que preenche todo o espaço disponível -->
      <img src="./assets/imagens/background.jpg" class="absolute-fill">
      <!-- Overlay sobre a imagem de fundo -->
      <div class="overlay d-flex half">
        <!-- Divisão da tela em duas metades -->
          <v-col cols="7">
            <div class="d-flex flex-column align-center">
              <spam>
                <h1 class="tittle d-flex flex-column align-center">
                  <u>PARE DE DESPERDIÇAR</u>
                  <u>DINHEIRO </u>
                  e maximize
                  <br>
                  <u>seus lucros</u>
                </h1>
              </spam>
              <p>
                <spam>Calcule sua redução de custos na gestão financeira de locações de imóveis com a plataforma Imobia
                </spam>
              </p>
              <strong>Reduzir seus custos operacionais e aumentar seu lucro bruto é seu objetivo?</strong>
              <div>
                <p>As empresas do mercado imobiliário estão buscando cada vez mais eficiência para organizar sua rotina
                  de cobranças e pagamentos de aluguéis.
                  Somos motivados a ajudar você a fazer uma gestão financeira de um jeito fácil e automático, vem com a
                  gente!</p>
              </div>
            </div>
          </v-col>
          <v-col cols="6">6</v-col>
      </div>
    </div>
    <AppFooter />
  </v-app>
</template>

<script setup>
//
</script>

<style scoped>
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.half {
  background-color: rgba(0, 0, 0, 0.5);
  /* Cor de fundo semi-transparente */
  color: white;
}

.tittle{
  color: #E94E24;
  font-size: 41px;
  font-family: Coda, display;
  text-align: center;
}
</style>