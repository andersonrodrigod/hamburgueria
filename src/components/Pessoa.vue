<template>
    <h2>Esta é a descrição da Pessoa: {{ name }}</h2>
</template>

<script>
    export default {
        name: 'Pessoa',
        data() {
            return {
                name: 'Rodrigo'
            }
        }
    }
</script>