<template>
    <div>
        <PrimeiroComponente/>
        <p>o dado é {{ testando }}</p>
        <LyfeCycle/>
        <Pessoa/>
    </div>
</template>

<script>
    import PrimeiroComponente from './components/PrimeiroComponente.vue'
    import LyfeCycle from './components/LyfeCycle.vue'
    import Pessoa from './components/Pessoa.vue'
  

    export default {
        name: 'App',
        components: {
            PrimeiroComponente,
            LyfeCycle,
            Pessoa,
        },
        data() {
            return {
                testando: 'teste'
            }
        }
    }
</script>