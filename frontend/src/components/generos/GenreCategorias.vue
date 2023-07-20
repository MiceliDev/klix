<template>
    <section>
        <p>{{ genre }}</p>
        <div>
            
        </div>
    </section>
</template>

<script>

    export default{
        name: 'GenreCategorias',
        props: {
            genre: String
        }
}
</script>

<style scoped>

section{
    width: 100vw;
    height: 35vh;
    display: flex;
    flex-direction: column;
}

section p{
    font-size: 2rem;
    color: snow;
    font-family: 'Roboto', sans-serif;
    font-weight: bold;
    padding: 5px;
}


section div{
    width: 100%;
    height: 80%;
    background: #000;
}

</style>