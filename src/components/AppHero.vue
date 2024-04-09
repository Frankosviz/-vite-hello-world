<template>
    <div class="container">
        <h1>{{ premessa }}</h1>

        <p>{{ presentazione }}</p>

        <img :src="imgPresentazione" alt="imgPresentazione">
    </div>
</template>

<script>
    export default {
        name: "AppHero",
        data(){
            return {
                premessa: 'Questa è la mia prima app con Vite!',
                presentazione : 'Benvenuti nel mio primo progetto con Vite, sono molto contento e non vedo l\'ora di iniziare ad implementare il codice con i nuovi comandi di Vite',
                imgPresentazione : './public/img/favicon.ico'
            }
        }
    }
</script>

<style scoped>
    .container {
        background-color: black;
        color: white;
        text-align: center;
        border: 1px solid black;
        border-radius: 10px;

    }
</style>