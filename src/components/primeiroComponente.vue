<template>
    <div>
        <h1>Olá Vue</h1>
        <p>Meu nome  é {{ name }} e trabalho como {{ job }}</p>
    </div>
</template>

<script>
    export default {
        name: 'PrimeiroComponente',
        data() {
            return {
                name: 'Rodrigo',
                job: 'Programador'
            }
        }
    }
</script>