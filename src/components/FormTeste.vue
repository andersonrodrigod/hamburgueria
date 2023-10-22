<template>
    <form action="">
        <div><ImputText/></div>
        <div><ImputText/></div>
        <div><ImputSubmit/></div>
    </form>
</template>

<script>
    import ImputSubmit from './form/ImputSubmit.vue'
    import ImputText from './form/ImputText.vue'
    export default {
        name: 'FormTeste',
        components: {
            ImputText,
            ImputSubmit
        }
    }
</script>