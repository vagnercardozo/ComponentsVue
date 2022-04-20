<script>
import NovoComponente from "./NovoComponente.vue";
export default {
  components: { NovoComponente },
};
</script>
<template>
  <main id="content">
    <NovoComponente class="NovoComponente" />
    <NovoComponente class="NovoComponente" />
    <NovoComponente class="NovoComponente" />
    <NovoComponente class="NovoComponente" />
    <NovoComponente class="NovoComponente" />
    <NovoComponente class="NovoComponente" />
  </main>
</template>
<style>
.NovoComponente {
  background-image: linear-gradient(to bottom right, red, yellow);
}
</style>
