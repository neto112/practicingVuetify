<template>
  <section class="pt-16">
    <v-container>
      <v-row class="d-flex justify-center">
        <v-col class="ml-10" cols="5">
          <div class="d-flex align-center" style="width: 30px; height: 30px">
            <v-img src="../assets/ingles.png" />
            <div class="ml-3">Inglês</div>
          </div>
          <p class="idade mt-4">A partir de 4 anos de idade</p>
          <p style="width: 27rem" class="mb-12">
            O idioma mais falado no mundo tem uma abordagem única com nosso
            método, onde a conversação é estimulada desde a primeira aula. Os
            alunos aprendem a formular frases de acordo com o que lhes é
            familiar, assimilando a gramática e o vocabulário de um modo muito
            melhor.
          </p>

          <div class="d-flex align-center" style="width: 30px; height: 30px">
            <v-img src="../assets/espanhol.png" />
            <div class="ml-3">Espanhol</div>
          </div>
          <p class="idade mt-4">A partir de 8 anos de idade</p>
          <p style="width: 27rem" class="mb-12">
            Um aprendizado dinâmico, repleto de atividades práticas e
            conversação. Progressivamente, o aluno adquire conhecimentos da
            gramática e de expressões, enquanto mergulha dentro da cultura dos
            países hispânicos.
          </p>

          <div class="d-flex align-center" style="width: 30px; height: 30px">
            <v-img src="../assets/frances.png" />
            <div class="ml-3">Francês</div>
          </div>
          <p class="idade mt-4">A partir de 15 anos de idade</p>
          <p style="width: 27rem" class="mb-12">
            Assim como o português, o francês também se originou do latim.
            Aproveitamos as semelhanças para que, através da conversação e de
            atividades práticas, o domínio do idioma seja cada vez mais natural.
          </p>

          <div class="d-flex align-center" style="width: 30px; height: 30px">
            <v-img src="../assets/alemao.png" />
            <div class="ml-3">Alemão</div>
          </div>
          <p class="idade mt-4">A partir de 15 anos de idade</p>
          <p style="width: 27rem" class="mb-12">
            Os alunos são imersos no idioma e na cultura alemã através da
            conversação, onde aprendem o vocabulário e expressões, levando em
            conta suas rotinas e necessidades, garantindo um aprendizado mais
            rápido e efetivo.
          </p>
        </v-col>
        <v-col cols="5">
          <div class="our">Nossos cursos</div>
          <p class="text mt-4">
            Ao aprender um novo idioma, as suas possibilidades se tornam
            infinitas. Vivemos em um mundo em que as fronteiras diminuem a cada
            dia, onde ter o domínio de outra língua pode sim transformar a vida
            de uma pessoa para melhor.
          </p>
          <p class="text mt-4">
            Desde impulsionar a vida profissional até proporcionar a coragem
            para viajar o mundo sem medo, compreender um segundo idioma tem
            diversas vantagens. Afinal, o idioma deve ser sempre sua forma de
            conexão e nunca limitação.
          </p>
          <p class="text mt-4">
            Para oferecer uma experiência completa, os cursos KNN são divididos
            em módulos, onde cada um é composto por vários livros. Os materiais
            didáticos são atualizados todos os anos, trazendo temas atuais e do
            cotidiano. Assim, nossos alunos estarão sempre preparados para
            qualquer situação que exigir um segundo idioma.
          </p>
          <p class="negrito mt-4">
            "Conheça nossos cursos e estude na KNN, uma das 5 maiores redes de
            ensino de idiomas da América Latina."
          </p>
          <v-btn x-large style="background: #F70052; color: white; width: 400px; height: 60px">QUERO MEU PRÊMIO</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: "Idiomas",
};
</script>

<style>

.ml-3 {
  font: normal normal bold 40px/48px Fira Sans, sans-serif;

}

.idade {
  font: italic normal 300 16px/19px Fira Sans, sans-serif;
}

.our {
  color: #6400ac;
  font: normal normal bold 40px/52px Fira Sans, sans-serif;
}

.text {
  font: normal normal 300 20px/28px Fira Sans, sans-serif;
}

.negrito {
  font: normal normal bold 36px/40px Fira Sans, sans-serif;
}
</style>