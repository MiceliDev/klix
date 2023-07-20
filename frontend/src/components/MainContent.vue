<template>
    <div>
        <p>Comédia</p>
        <GenreCategorias />
        <p>Históricos</p>
        <GenreCategorias />
        <p>Clipes</p>
        <GenreCategorias />
        <p>Criminais</p>
        <GenreCategorias />
        <p>Cursos</p>
        <GenreCategorias />
        <p>Motivacionais</p>
        <GenreCategorias />

    </div>
</template>

<script>
    import GenreCategorias from "./generos/GenreCategorias.vue";

    export default{
        name: 'MainContent',
        components :{
            GenreCategorias
        },
        data
    }
</script>

<style scoped>
    div{
        width: 100vw;
    }

    div p{
    font-size: 2rem;
    color: snow;
    font-family: 'Roboto', sans-serif;
    font-weight: bold;
    padding: 5px;
}
</style>