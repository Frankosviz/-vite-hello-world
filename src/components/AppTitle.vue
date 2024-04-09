<template>
        <!-- Nel template inserisco il mio titolo in un div container -->
    <div class="container">
        <h1>{{ title }}</h1>
    </div>
</template>

<script>
export default {
        // Nel mio script inizio dando un nome a questo componente, mi servirà nella App.vue per richiamarlo nel template
    name: 'AppTitle',
    data() {
        // Nei data gli faccio ritornare una stringa di testo
        return {
            title: 'La mia prima App con vite!'
        }
    }

}
</script>

<style scoped>
/* Aggiungo qualche stile css al mio componente */
.container {
    background-color: black;
}
h1 {
    color: red;
    text-align: center;
    font-size: 50px;
}
</style>