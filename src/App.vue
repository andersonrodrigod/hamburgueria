<template>
    <div>
        <PrimeiroComponente/>
        <p>o dado é {{ testando }}</p>
        <LyfeCycle/>
        <PessoaIndividuo/>
    </div>
</template>

<script>
    import PrimeiroComponente from './components/PrimeiroComponente.vue'
    import LyfeCycle from './components/LyfeCycle.vue'
    import PessoaIndividuo from './components/PessoaIndividuo.vue'
  

    export default {
        name: 'App',
        components: {
            PrimeiroComponente,
            LyfeCycle,
            PessoaIndividuo
        },
        data() {
            return {
                testando: 'teste'
            }
        }
    }
</script>