<template>

  <Navbar />
  <Perfil />
  <Experiencia />
  <Proyectos />
  <Sobremi />
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Perfil from './components/Perfil.vue'
import Experiencia from './components/Experiencia.vue'
import Proyectos from './components/Proyectos.vue'
import Sobremi from './components/Sobremi.vue'

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
:root {
  color-scheme: dark;
  background: rgb(1,0,14);
  background: linear-gradient(23deg, rgba(1,0,14,1) 44%, rgba(72,72,91,1) 99%);

}
body {
  margin: 0px;
}
</style>
