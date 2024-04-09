<template>
    <div class="container">
        <em>{{ msgFooter }}</em>
    </div>
</template>

<script>
export default {
        // Nel mio script inizio dando un nome a questo componente, mi servirà nella App.vue per richiamarlo nel template
    name: 'AppFooter',
    data() {
        // Nei data gli faccio ritornare una stringa di testo
        return {
            msgFooter : 'Made with love by Francesco'
        }
    }

}
</script>

<style scoped>
    .container {
        margin-top: 20px;
        background-color: black;
        color: white;
        font-weight: lighter;
        border-radius: 10px;
        text-align: center;
    }
</style>