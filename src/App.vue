<script>
import MenuLateral from "@/components/MenuLateral.vue";
import Cabecalho from "@/components/Cabecalho.vue";
import Rodape from "@/components/Rodape.vue";
import Principal from "@/components/Principal.vue";

export default {
  components: { MenuLateral, Cabecalho, Rodape, Principal },
};
</script>
<template>
  <MenuLateral />
  <Cabecalho />
  <Principal /> 
  <Rodape />
</template>
<style></style>
