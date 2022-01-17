<template>
  <section>
    <GiftShow />
    <Driver />
    <Caminho />
    <Idiomas />
    <Last />
  </section>
</template>

<script>
import GiftShow from "../components/GiftShow.vue";
import Driver from "../components/Driver.vue";
import Caminho from "../components/Caminho.vue";
import Idiomas from "../components/Idiomas.vue";
import Last from "../components/Last.vue";

export default {
  components: {
    GiftShow,
    Driver,
    Caminho,
    Idiomas,
    Last,
  },
};
</script>

