<template>
  <PrimeiroComponente />
  <LiveCicle />
  <Pessoa />
</template>

<script>
import PrimeiroComponente from "./components/PrimeiroComponente.vue";
import LiveCicle from "./components/LiveCicle.vue";
import Pessoa from "./components/Pessoa.vue";

export default {
  name: "App",
  components: {
    PrimeiroComponente,
    LiveCicle,
    Pessoa,
  },
};
</script>
