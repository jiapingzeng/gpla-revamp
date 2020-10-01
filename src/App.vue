<template>
  <div id="app">
    <router-view />
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
  </div>
</template>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

#nav {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  padding: 30px;
  text-align: center;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin: 0.3em;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

body {
  margin: 0;
}
</style>
