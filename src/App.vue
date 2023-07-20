<template>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <Home />
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
html{
  height: 100%;
  max-width: 1921;
}
body{
  margin: 0px;
  height: 100%;
  max-width: 1921;
}
#app{
height: 100%;
}
.wrapper{
  display: flex;
  align-items: center;
  flex-direction: column;
  flex: 1 1 auto;
  overflow:hidden;
}
.container{
  max-width: 1254px;
  margin: 0px auto;
  height: 100%;
}
</style>
