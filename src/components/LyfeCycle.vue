<template>
    <h1>Meu nome é {{ name }}</h1>
</template>

<script>
    export default {
        name: 'LyfeCycle',
        data() {
            return {
                name: 'Ainda não sei'
            }
        },
        created() {
            setTimeout(() => {
                this.name = 'Rodrigo'
            }, 1000)
            
        },
        mounted() {
            setTimeout(() => {
                this.name = 'Anderson'
            }, 2000)
        }
    }
</script>