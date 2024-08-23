<script>
// Código Javascript aqui
  export default {
    data() {
        return {
            message: "Bem Vindo Fulano!!!",
            corpo: "Corpo do texto",
            count: 0
        }
    }
  }
</script>

<template>
  <header class="mb-5" id="header">
      <!-- Cabeçalho -->
      <nav class="navbar navbar-light border-bottom">
          <div class="container-fluid">
            <a class="navbar-brand" href="#">
              <img src="./assets/img/logo-firjan.png" alt="Logo" class="logo-firjan">
            </a>
          </div>
      </nav>
      <div class="container-fluid mt-5 text-center">
          <h1>Curso Programador FrontEnd</h1>
          <!-- <h2>Disciplina: Desenvolvimento Web</h2>
          <h3>{{ message }}</h3>
          <h4>{{ corpo }}</h4> -->
      </div>
  </header>
  <main class="container" id="app">
      <!-- Conteúdo -->
      <h3>{{ message }}</h3>
      <h4>{{ corpo }}</h4>
      <hr>

      <p v-show="count > 0">Contagem atual: {{ count }}</p>

      <button class="btn btn-warning" @click="count--" :disabled="count <= 0">Decrementar</button> | 
      <button class="btn btn-primary" @click="count++">Incrementar</button>

      <div v-if="count > 0">
          <p>Objeto count está sendo atualizado.</p>
      </div>
      <div v-else>
          <p>Objeto count tem como valor o 0.</p>
      </div>

  </main>
  <footer class="container-fluid fixed-bottom bg-dark">
      <!-- Rodapé -->
        <div class="f-info">
          <span>Desenvolvido por [SEU NOME] 2024&COPY;</span>
        </div>
  </footer>
</template>

<style scoped>
/* Código CSS aqui */
</style>
