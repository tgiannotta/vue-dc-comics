<template>
  <div id="app">
    <div class="container">
      <Header /> 
      <main>
      <h2>I contenuti andranno qui</h2>
   </main>
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

<style lang="scss">
@import "./style/general.scss";
#app {
    main{
     
    color: orange;
    background-color: black;
    height: 200px;
    
  }
  
}
</style>
