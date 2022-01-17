<template>
  <section class="caminho">
    <v-container>
      <v-row class="d-flex align-center justify-center white--text">
        <v-col class="d-flex align-center justify-center" cols="4">
          <div class="pa-16">
            <p class="caminho-1 white--text">
              Porque a KNN é a melhor escolha?
            </p>
            <p class="caminho-2 white--text">
              Nosso método de ensino foi desenvolvido exclusivamente para
              pessoas que falam português, trazendo para dentro de sala de aula
              os gostos pessoais de cada aluno.
            </p>
            <p class="caminho-2 white--text">
              Com mais de 600 unidades pelo Brasil, a KNN Idiomas acelera o que
              é fácil e facilita o que é difícil. Já para manter a atenção do
              aluno, seus gostos e interesses pessoais são levados para dentro
              da sala, tornando a aula muito mais dinâmica.
            </p>
            <p class="caminho-2 white--text">
              A criatividade dos alunos é estimulada através de conversação do
              início ao fim das aulas, par que a habilidade da fala seja
              trabalhada em todas as lições. A fluência é atingida rapidamente,
              com o aluno percebendo claramente sua constante evolução.
            </p>
            <v-btn class="negrito red--text" color="white" style="width: 380px; height: 60px">QUERO MEU PRÊMIO</v-btn>
          </div>
        </v-col>
        <v-col class="meio" cols="6">
          <v-row>
            <v-col class="d-flex align-end justify-center">
              <img src="../assets/van.png" alt="">
            </v-col>
            <v-col class="d-flex align-end justify-center">
              <img src="../assets/bandeira.png" alt="">
            </v-col>
            <v-col class="d-flex align-end justify-center">
              <img src="../assets/phone.png" alt="">
            </v-col>
          </v-row>
          <v-row>
            <v-col>
              <p class="font-italic">Transporte gratuito para<br> alunos até 14 anos</p>
            </v-col>
            <v-col>
              <p class="font-italic">Metodologia criada para<br> quem fala português</p>
            </v-col>
            <v-col>
              <p class="font-italic">Aplicativo educacional</p>
            </v-col>
          </v-row>
          <v-row>
            <v-col class="d-flex align-end justify-center">
              <img src="../assets/msg.png" alt="">
            </v-col>
            <v-col class="d-flex align-end justify-center">
              <img src="../assets/bookpencil.png" alt="">
            </v-col>
            <v-col class="d-flex align-end justify-center">
              <img src="../assets/book.png" alt="">
            </v-col>
          </v-row>
          <v-row>
            <v-col>
              <p class="font-italic">Conversação imediata</p>
            </v-col>
            <v-col>
              <p class="font-italic">Reforço pedagógico<br> gratuito</p>
            </v-col>
            <v-col>
              <p class="font-italic">Material didático<br> atualizado anualmente</p>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: "Caminho",
};
</script>

<style>
.caminho {
  background: #6400ac 0% 0% no-repeat padding-box;
}

.caminho-1 {
  font: normal normal bold 50px/52px Fira Sans, sans-serif;
}

.caminho-2 {
  font: normal normal 300 20px/24px Fira Sans, sans-serif;
}

.meio {
  text-align: center;
}


</style>