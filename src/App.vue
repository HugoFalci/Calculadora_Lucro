<template>
  <v-app>
    <v-img src="./assets/imagens/background.jpg" cover>
      <!-- Adicionando uma camada fosca com um div -->
      <div class="frosted-layer"></div>
        <v-container>
          <v-row >
            <v-col cols="6" align-self="center" class="lado_esquerdo pa-5 pt-16 mt-10 ml-10">
              <v-card flat class="bg-transparent mt-16 text-center">
                <h1 class="titulo text-tituloLaranja font-weight-bold">
                  <spam class="underline-uppercase">PARE DE DESPERDIÇAR </spam>
                  <spam class="underline-uppercase">DINHEIRO</spam> e maximize
                  <spam class="underline-uppercase">seus lucros</spam>
                </h1>

                <h2 class="subtitulo_caucule_reducao text-tituloLaranja text-center font-weight-bold mt-2 ">
                  Calcule sua redução de custos na gestão financeira de locações de imóveis com a
                  plataforma Imobia
                </h2>

                <div class="conteudo text-white pa45 pt-5">
                  <b>Reduzir seus custos operacionais e aumentar seu lucro bruto é seu objetivo?</b>
                  <br><br>
                  As empresas do mercado imobiliário estão buscando cada vez mais eficiência 
                  para organizar sua rotina de cobranças e pagamentos de aluguéis. 
                  Somos motivados a ajudar você a fazer uma gestão financeira de um jeito fácil e automático, 
                  vem com a gente!
                </div>
              </v-card>
            </v-col>
            <v-col cols="5">
              <v-card>
                teste               
              </v-card>
            </v-col>
          </v-row>
        </v-container>
    </v-img>
    <AppFooter />
  </v-app>
</template>

<script setup>
//
</script>

<style scoped>
.lado_esquerdo {
  line-height: 1.2;
  text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.5)
}

.titulo {
  font-size: 43px;
}

.subtitulo_caucule_reducao {
  font-size: 30px;
  letter-spacing: 3px;
}

.conteudo {
  font-size: 25px;
}

.frosted-layer {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgb(30, 50, 96, 0.66);
  /* Cor branca com opacidade de 50% */
}

.underline-uppercase {
  display: inline-block;
  text-decoration: underline;
}
</style>