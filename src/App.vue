<template>
  <div id="app">
    <div class="nav">
      <div class="brand">
        <router-link to="/">Kiana Cao!</router-link>
      </div>
      <div class="nav-item">
        <router-link to="/work">WORK</router-link>
        <a>RESUME</a>
        <a>CONTACT</a>
      </div>
    </div>
    <router-view />
  </div>
</template>

<!-- Your global styles here -->
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 50px;
  padding: 0 50px;
  margin-bottom: 15px;
  border-bottom: 1px solid lightgray;
}

.nav-item a {
  font-weight: bold;
  color: #2c3e50;
  margin-right: 25px;
}

.nav-item a.router-link-exact-active {
  color: #42b983;
}
</style>
