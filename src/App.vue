<template>
  <div id="nav">
    <div class="nav1">
      <div class="w3-bar w3-border w3-card-4">
        <router-link to="/" class="w3-bar-item w3-button">Home</router-link>
        <router-link to="/about" class="w3-bar-item w3-button"
          >About</router-link
        >
        <router-link to="/services" class="w3-bar-item w3-button"
          >Services</router-link
        >
        <div class="w3-dropdown-hover">
          <button class="w3-button">Dropdown</button>
          <div class="w3-dropdown-content w3-card-4">
            <router-link to="/" class="w3-bar-item w3-button">Home</router-link>
            <router-link to="/about" class="w3-bar-item w3-button"
              >About</router-link
            >
            <router-link to="/services" class="w3-bar-item w3-button"
              >Services</router-link
            >
          </div>
        </div>
      </div>
    </div>
    <div class="nav2">
      <div class="w3-bar w3-border w3-card-4">
        <div class="w3-dropdown-hover">
          <button class="w3-button">Dropdown</button>
          <div class="w3-dropdown-content w3-card-4">
            <router-link to="/" class="w3-bar-item w3-button">Home</router-link>
            <router-link to="/about" class="w3-bar-item w3-button"
              >About</router-link
            >
            <router-link to="/services" class="w3-bar-item w3-button"
              >Services</router-link
            >
          </div>
        </div>
      </div>
    </div>
  </div>
  <router-view />
  <footer class="footer">
    <div class="w3-container text-center">JavaScript Web Apps</div>
  </footer>
</template>

<script>
import * as mdb from "mdb-ui-kit";

export default {
  mdb,
};
</script>

<style lang="scss">
@import "./assets/navBar.css";
@import "./assets/main.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding-bottom: 80px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b5b9;
    }
  }
}
</style>
