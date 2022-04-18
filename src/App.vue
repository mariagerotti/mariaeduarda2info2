<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoCabecalho from "@/components/BloclCabecalho.vue"

export default {
  components: { MenuLateral, BlocoCabecalho },
};
</script>

<template>
  <MenuLateral />
  <header class="header">cabeçalho</header>
  <main class="content">principal</main>
  <footer class="footer">rodape</footer>
</template>
