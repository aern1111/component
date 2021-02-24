<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Hungryeatsfood</router-link> |
      <router-link to="/about">Menu</router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background: #9cd4bb;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  font: 1em sans-serif;
}

#nav a.router-link-exact-active {
  color: #42b983;
  font: 2em sans-serif;
}
</style>
