<script>
    // Código Javascript aqui
    export default {
        data() {
            return {
                // Propriedades aqui.
            }
        },
    }
</script>
<template>
    <!-- Código HTML aqui -->
    <h2 class="subtitulo">Entre em contato conosco.</h2>
    <section class="container mb-3">
        <form @submit.prevent>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Nome:</label>
                <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Informe seu nome">
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Contato:</label>
                <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Informe o telefone/celular">
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Email:</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="email@example.com">
            </div>
            <div class="mb-3">
                <label for="exampleFormControlInput1" class="form-label">Assundo:</label>
                <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="email@example.com">
            </div>
            <div class="mb-3">
                <label for="exampleFormControlTextarea1" class="form-label">Mensagem:</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
            </div>
            <div class="mb-3">
                <button class="btn btn-primary">Enviar</button>
            </div>
        </form>
    </section>
</template>
<style scope>
    /* Estilização CSS aqui */
</style>
