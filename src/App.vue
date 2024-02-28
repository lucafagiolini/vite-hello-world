<!-- ********** JS ********** -->
<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    AppTitle,
    AppHero
  }

}
</script>





<!-- ********** HTML ********** -->
<template>
  <div id="giovanni">
    <AppTitle />
    <AppHero />
  </div>
</template>




<!-- ********** CSS ********** -->    
<style>
#giovanni {
  font-family: sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

body {
  padding: 100px;
}

BUtton {
  background-color: #4CAF50;
  border: none;
  color: #2a3036;
  padding: 12px 22px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 1.2rem;
  font-weight: bold;
  margin: 4px 2px;
  cursor: pointer;
  border-radius: 0.4rem;
}
</style>