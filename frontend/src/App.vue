<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/product">Product</router-link> |
      <router-link to="/register">Register</router-link> 
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #ff0000;
}

#nav a.router-link-exact-active {
  color: #00ffd5;
}
</style>
