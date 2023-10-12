<template>
    <div>
        <PrimeiroComponente/>
        <p>o dado é {{ testando }}</p>
    </div>
</template>

<script>
    import PrimeiroComponente from './components/PrimeiroComponente.vue'
    export default {
        name: 'App',
        components: {
            PrimeiroComponente
        },
        data() {
            return {
                testando: 'teste'
            }
        }
    }
</script>