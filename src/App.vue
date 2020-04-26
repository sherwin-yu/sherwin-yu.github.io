<template>
  <div id="app">
    <div class="nav">
      <div class="brand">
        <router-link to="/">Kiana Cao</router-link>
      </div>
      <div class="nav-item">
        <router-link to="/work">WORK</router-link>
        <router-link to="/about">ABOUT</router-link>
        <router-link to="/contact">CONTACT</router-link>
      </div>
    </div>
    <router-view />
  </div>
</template>

<!-- Your global styles here -->
<style lang="scss">
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
  border-bottom: 1px solid lightgray;
}

.brand {
  a {
    text-decoration: none;
    color: black;
    font-size: 18px;
    padding: 15px;
  }
}

.nav-item {
  a {
    font-weight: bold;
    color: #2c3e50;
    margin-right: 25px;
    text-decoration: none;
  }
}
</style>
