<template>
    <div>
        <nav>
            <ul>
                <li><ion-icon name="home-outline"></ion-icon></li>
                <li>Filmes</li>
                <li>Séries</li>
                <li>Favoritos</li>
            </ul>
            <input type='text' placeholder="Busca..." />
        </nav>
    </div>
</template>

<script>
export default {
    name: 'MenuBar'
}
</script>

<style scoped>
div{
    position: fixed;
    z-index: 2;
    width: 50vw;
    margin-top: 90px;
    left: calc(-50vw / 2);
    margin-left: 50%;
    background: #181212;
}

nav{
    width: 100%;
    height: 60px;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;

}

nav li{
    list-style: none;
    display: inline;
    font-family: 'Roboto', sans-serif;
    color: azure;
    font-size: 20px;
    padding: 0 30px;
}

nav li:hover{
    color: rgb(31, 116, 20);
}

nav input{
    padding: 20px;
    width: 40%;
    height: 15px;
    background: #292323;
    border: none;
    color: #fff;
    font-family: 'Roboto', sans-serif;
    font-size: 18px;
}


</style>