<script>
    // Código Javascript aqui
    export default {
        data() {
            return {
                // Propriedades aqui
            }
        }
    }
</script>
<template>
    <!-- Código HTML aqui -->
    <header class="mb-5">
      <!-- Cabeçalho -->
      <nav class="navbar navbar-expand-lg bg-body-tertiary border-bottom navbar-light">
        <div class="container-fluid">
            <!-- <a class="navbar-brand" href="#/">HOME</a> -->
            <!-- <router-link to="/">HOME</router-link> -->
            <RouterLink to="/" class="navbar-brand">
                <img src="../assets/img/logo-firjan.png" alt="Logo" class="logo-firjan">
                HOME
            </RouterLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                <!-- <a class="nav-link" href="#/sobre">SOBRE</a> -->
                <RouterLink to="/sobre" class="nav-link">SOBRE</RouterLink>
                <!-- <router-link to="/sobre">SOBRE</router-link> -->
                </li>
                <li class="nav-item">
                <!-- <a class="nav-link" href="#/contato">CONTATO</a> -->
                <!-- <router-link to="/contato">CONTATO</router-link> -->
                <RouterLink to="/contato" class="nav-link">CONTATO</RouterLink>
                </li>
            </ul>
            </div>
        </div>
        </nav>
      <div class="container-fluid mt-5 text-center">
          <h1>Curso Programador FrontEnd</h1>
      </div>
    </header>
</template>
<style>
    /* Estilização CSS aqui */
</style>