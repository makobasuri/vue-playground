<template>
  <div id="app">
    <app-header></app-header>
    <router-view></router-view>
    <app-footer></app-footer>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
body {
  font-family: 'Fira Sans', Helvetica, Arial, sans-serif;
  box-sizing: border-box;
  margin: 0;
  width: 100%;
  height: 100%;
  padding: 0;
}

body * {
  box-sizing: inherit;
}

a {
  text-transform: uppercase;
  text-decoration: none;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
