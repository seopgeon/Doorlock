<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
  <!-- <router-view/> -->
  <table>
  <tr>
    <td><img src="../image/doorbell.png" alt="Button 1"></td>
    <td><img src="../image/doorlock.png" alt="Button 2"></td>
    <td><button type="button"> <img src="../image/doorlock.png" height ="240" width="240" /></button>도어락</td>
  </tr>
  <tr>
    <td><img src="../image/setting.png" alt="Button 3"></td>
    <td><img src="../image/doorlock.png" alt="Button 2"></td>
  </tr>
  <tr>
    <td><img src="../image/doorbell.png" alt="Button 1"></td>
    <td><img src="../image/doorlock.png" alt="Button 2"></td>
  </tr>
</table>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
