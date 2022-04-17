<template>
  <!-- if -->
  <h1 v-if="mostrarInfo">{{ info }}</h1>
  <h1 v-else>Sem permissão</h1>

  <!-- show -->
  <h1 v-show="mostrarInfo">{{ info }}</h1>
</template>

<script>
export default {
  name: "InfoPessoa",
  props: {
    info: String,
    mostrarInfo: Boolean,
  },
};
</script>
