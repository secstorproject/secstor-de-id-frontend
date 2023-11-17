<template>
  <div id="app" class="h-100 d-flex">
    <div class="main-content bg-light flex-grow-1">
      <AnonymizeForm />
    </div>
  </div>
</template>

<script>
import AnonymizeForm from './components/AnonymizeForm.vue';

export default {
  components: {
    AnonymizeForm,
  },
};
</script>

<style>
/* Estilize o componente "App.vue" conforme necessário */
#app {
  height: 100vh;
}

.sidebar {
  flex: 0 0 250px; /* Largura da sidebar */
  overflow-y: auto; /* Permite scroll se o conteúdo for maior que a altura da sidebar */
}

.main-content {
  /* Ocupa o restante do espaço disponível */
  flex-grow: 1;
  overflow-y: auto; /* Permite scroll se o conteúdo for maior que a altura da página */
}
</style>
