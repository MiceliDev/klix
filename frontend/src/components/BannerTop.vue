<template>
    <div>
        <button>
            <span>Assista Agora</span>
            <ion-icon name="play-outline"></ion-icon>
        </button>
    </div>
</template>

<script>

    export default{
        name: 'BannerTop'
    }
</script>

<style scoped>
    div{
        width: 100vw;
        height: 55vh;
        background-image: url('../assets/img/chaves_banner.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        display: flex;
        flex-direction:column-reverse;

    }

    button{
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
        color:#e0dddd;
        width: 250px;
        height: 60px;
        background: rgb(24, 61, 10);
        margin: 100px;
        border:none;
        font-size: 25px;
        font-weight: bold;

    }
</style>