<script>
// Importo componente AppTitle.vue
import AppTitle from "./components/AppTitle.vue";

// Importo componente AppHero.vue
import AppHero from "./components/AppHero.vue";

// Esporto componenti
export default {
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<!-- Inserisco componenti nel template -->
<template>
  <AppTitle />
  <AppHero />
</template>
