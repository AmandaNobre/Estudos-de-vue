<template>
  <div>
    <h1>Pessoa {{ nome }}</h1>

    <!-- v-bind: para especificar como boolean -->
    <InfoPessoa info="Informações da pessoa" v-bind:mostrarInfo="true" />
  </div>
</template>

<script>
import InfoPessoa from "./InfoPessoa.vue";

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Pessoa",
  components: { InfoPessoa },
  data() {
    return { nome: "Amanda", descricao: "desc" };
  },
};
</script>
