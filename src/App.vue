<script>
  // Código Javascript aqui
  import Header from './components/Header.vue';
  import Home from './components/Home.vue';
  // import Sobre from './components/Sobre.vue';
  // import Contato from './components/Contato.vue';
  import Footer from './components/Footer.vue';
  export default {
    components: {
      Header,
      Footer,
      Home,
      // Sobre,
      // Contato,
    },
    data() {
        return {
          //page: "home"
        }
    }
  }
</script>

<template>
  <!-- Blocos/Componentes aqui -->
  <Header />
  <main class="container d-flex flex-column">
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#" @click="page = 'home'">HOME</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#" @click="page = 'sobre'">SOBRE</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#" @click="page = 'contato'">CONTATO</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section>
      <Home />
    </section>
    <!-- <section v-if="page == 'home'">
      <Home />
    </section>
    <section v-else-if="page == 'sobre'">
      <Sobre />
    </section>
    <section v-else-if="page == 'contato'">
      <Contato />
    </section> -->
  </main>
  <Footer />
</template>

<style scoped>
/* Código CSS aqui */
main {
  margin-bottom: 100px;
}
</style>