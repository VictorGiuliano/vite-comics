<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  name: 'Home Comics',
  components: { AppHeader, AppMain, AppFooter }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
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
  max-width: 900px;
  margin: 0 auto;

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
