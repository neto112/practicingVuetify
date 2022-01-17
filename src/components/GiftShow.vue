<template>
  <section class="gift-show">
    <v-container>
      <v-row>
        <v-col>
          <v-row>
            <v-col cols="6" class="YouWin">
              <img src="../assets/You.Win.png" alt="" />
            </v-col>
            <v-col cols="2" class="Porcentagem">
              <img src="../assets/porcentagem.png" alt="" />
            </v-col>
            <v-col cols="2" class="Coracao">
              <img src="../assets/coracao.png" alt="" />
            </v-col>
            <v-col cols="2" class="Presente">
              <img src="../assets/presente.png" alt="" />
            </v-col>
            <v-col cols="2" class="Estrela">
              <img src="../assets/estrela.png" alt="" />
            </v-col>
            <v-col cols="2" class="ShowPremio">
              <img src="../assets/showdepremio.png" alt="" />
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="4">
          <v-form class="form rounded-xl my-16">
            <div class="pa-16">
              <p class="gift-show-cadastre">
                Cadastre-se e
                <span>descubra o que a KNN preparou para você.</span>
              </p>
              <p class="gift-show-texto">
                Você já deu o primeiro passo para mudar o futuro. Agora preencha
                o formulário abaixo e libere o seu prêmio.
              </p>
              <v-text-field outlined label="Nome"></v-text-field>
              <v-text-field outlined label="E-mail"></v-text-field>
              <v-text-field outlined label="Telefone"></v-text-field>
              <v-text-field outlined label="Cidade"></v-text-field>
              <div class="text-center">
                <v-dialog v-model="dialog" width="500">
                  <template v-slot:activator="{ on, attrs }">
                    <v-btn
                      color="red"
                      dark
                      v-bind="attrs"
                      v-on="on"
                      style="width: 440px; height: 60px"
                    >
                      QUERO MEU PRÊMIO
                    </v-btn>
                  </template>

                  <v-card class="cor rounded-lg">
                    <v-card-actions class="justify-end white--text">
                      <v-btn
                        @click="dialog = false"
                        class="white--text"
                        color="#6400AC"
                        text
                      >
                        X
                      </v-btn>
                    </v-card-actions>

                    <v-card-text class="white--text">
                      <p class="um">PARABÉNS!</p>
                      <p class="um">VOCÊ GANHOU</p>
                      <p class="dois mt-10">30%</p>
                      <p class="tres mt-15">DE DESCONTO</p>
                      <p class="nove">NA SUA MENSALIDADE</p>
                      <p class="quatro"></p>
                      <p class="cinco rounded-lg" dark>
                        CÓDIGO: <span>UBER30KNN</span>
                      </p>
                      <p class="seis">
                        Print essa tela, vá até uma de nossas unidades* e
                        <span class="sete">garanta seu desconto.</span>
                      </p>
                      <p class="oito">*Balneário Camboriú, Itapema e Itajaí</p>
                    </v-card-text>
                  </v-card>
                </v-dialog>
              </div>
            </div>
          </v-form>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: "GiftShow",
};
</script>

<style lang="scss">
.index {
  z-index: 1;
}

.YouWin {
  position: relative;

  img {
    position: absolute;
    top: -7rem;
    left: 8rem;
    z-index: 0;
  }
}

.Porcentagem {
  position: relative;

  img {
    position: absolute;
    top: 30rem;
    left: -15rem;
    z-index: 0;
  }
}

.Coracao {
  position: relative;

  img {
    position: absolute;
    top: 7rem;
    left: 19rem;
    z-index: 0;
  }
}

.Presente {
  position: relative;

  img {
    position: absolute;
    top: 27rem;
    left: 42rem;
    z-index: 0;
  }
}

.Estrela {
  position: relative;

  img {
    position: absolute;
    top: 31rem;
    left: 64rem;
    z-index: 0;
  }
}

.ShowPremio {
  position: relative;

  img {
    position: absolute;
    top: -1rem;
    left: 12rem;
    z-index: 0;
  }
}

.gift-show {
  background: transparent linear-gradient(116deg, #6400ac 0%, #f70052 100%) 0%
    0% no-repeat padding-box;
}

.gift-show form {
  background: #f2f7ff;
}

.form {
  border-style: solid;
  border-color: #3e009f;
  border-width: medium;
}

.gift-show-cadastre {
  color: #3e009f;
  font: normal normal normal 32px/34px Fira Sans, sans-serif;
}

.gift-show-cadastre span {
  font: normal normal bold 32px/34px Fira Sans, sans-serif;
}

.cor {
  background: transparent linear-gradient(131deg, #6400ac 0%, #f70052 100%) 0%
    0% no-repeat padding-box;
  text-align: center;
}

.um {
  font: normal normal 36px/47px Fira Sans, sans-serif;
}

.dois {
  font: normal normal 800 136px/47px Fira Sans, sans-serif;
}

.tres {
  font: normal normal bold 36px/47px Fira Sans, sans-serif;
}

.nove {
  font: normal normal normal 36px/47px Fira Sans, sans-serif;
}

.quatro {
  font: normal normal normal 36px/47px Fira Sans, sans-serif;
}

.cinco {
  font: normal normal normal 40px/46px Fira Sans, sans-serif;
  background: #fff;
  color: #6400ac;
}

.cinco span {
  font: normal normal bold 40px/46px Fira Sans, sans-serif;
}

.seis {
  font: italic normal normal 27px/31px Fira Sans, sans-serif;
}

.sete {
  font: italic normal bold 27px/31px Fira Sans, sans-serif;
}

.oito {
  font: italic normal 300 19px/31px Fira Sans, sans-serif;
}
</style>