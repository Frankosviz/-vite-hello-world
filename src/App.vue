<template>
    <AppTitle />
    <AppHero />
    <AppFooter />
</template>

<script>
    import AppTitle from './components/AppTitle.vue'
    import AppHero from './components/AppHero.vue'
    import AppFooter from './components/AppFooter.vue'
    export default {
        name: 'App',

        components: {
            AppTitle,
            AppHero,
            AppFooter
        },
        data(){
            return {
            }
        },

        
    }
</script>

<style scoped>

</style>


