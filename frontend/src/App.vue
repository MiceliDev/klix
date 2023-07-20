<template>
  <div>
    <MenuBar />
    <TopoBar />
    <BannerTop />
    <MainContent />
  </div>
  
</template>

<script>
import TopoBar from './components/TopoBar.vue'; //Importação do TopoBar
import MenuBar from './components/MenuBar.vue'; //Importação do MenuBar
import BannerTop from './components/BannerTop.vue'; //Importação do banner dinâmico
import MainContent from  './components/MainContent.vue'; //Importação do Main junto as categoris de generos e seus conteúdos

export default {
  name: 'App',
  components: {
    TopoBar,
    BannerTop,
    MenuBar,
    MainContent
  }
}
</script>

<style>
  *{
    margin:0;
    padding: 0;
    box-sizing: border-box;
  }

  body{
    margin:0;
    padding: 0;
    background: #444141;
  }


</style>
