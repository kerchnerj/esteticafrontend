<script>
import tabelaClientes from "./tabelaClientes.vue";
export default {
  components: { tabelaClientes },
};
</script>
<template>
  <section>
    <h2>Clientes</h2>
    <tabela-clientes />
  </section>
</template>
<style scoped>
section {
  margin-top: 1em;
}
</style>
