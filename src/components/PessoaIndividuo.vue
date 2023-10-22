<template>
    <div>
        <h2>Esta é a descrição da Pessoa: {{ name }}</h2>
        <InfoPessoa/>
        <FormTeste/>
    </div>
</template>

<script>
    import InfoPessoa from './InfoPessoa.vue'
    import FormTeste from './FormTeste.vue'
    export default {
    name: 'PessoaIndividuo',
    components: {
        InfoPessoa,
        FormTeste,
    },
    data() {
        return {
            name: 'Rodrigo'
        };
    },
}
</script>