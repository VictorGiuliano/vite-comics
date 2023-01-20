<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
  name: 'Home Comics',
  components: { AppHeader, AppMain }
}
</script>

<template>
  <AppHeader />
  <AppMain />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  min-height: 100vh;
}

.container {
  max-width: 1200px;
  margin: 0 100px;
  padding: 0 20px;
}

ul {
  display: flex;
  justify-content: center;
  align-items: center;
}

li {
  list-style-type: none;
}

a {
  text-decoration: none;
  padding: 3rem 0.57rem;
  color: black;
}

a:hover,
a:active {
  color: blue;
  border-bottom: blue solid 2px;
}

img {
  max-width: 100%;
  height: auto;
}
</style>
