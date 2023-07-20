<template>
    <div>
        <GenreCategorias genre="Comédia"/>
        <GenreCategorias genre="Histórico"/>
        <GenreCategorias genre="Clipes"/>
        <GenreCategorias genre="Criminais"/>
        <GenreCategorias genre="Cursos"/>
        <GenreCategorias genre="Jogos"/>

    </div>
</template>

<script>
    import GenreCategorias from "./generos/GenreCategorias.vue";

    export default{
        name: 'MainContent',
        components :{
            GenreCategorias
        },
    }
</script>

<style scoped>
    div{
        width: 100vw;
    }
</style>