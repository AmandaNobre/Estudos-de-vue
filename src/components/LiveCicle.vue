<template>
  <h1>Menu nome é: {{ nome }}</h1>
</template>

<script>
export default {
  name: "LiveCicle",
  data() {
    return {
      nome: "Não sei",
    };
  },
  created() {
    setTimeout(() => {
      this.nome = "Amanda";
    }, 1000);
  },
  mounted() {
    setTimeout(() => {
      this.nome = "Nobre";
    }, 2000);
  },
};
</script>
