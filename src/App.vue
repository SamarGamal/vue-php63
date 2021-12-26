<template>
  <div id="app">
    <div id="nav" class="container">
      <div>
        <b-navbar toggleable="lg" type="light" variant="">
          <b-navbar-brand href="#">
            <img src="@/assets/img/logo.png" alt="logo">
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <!-- Right aligned nav items -->
            <b-navbar-nav class="ms-auto">
              <b-nav-item>
                <router-link to="/">Home</router-link>
              </b-nav-item>
              <b-nav-item>
                <router-link to="/about">About</router-link>
              </b-nav-item>
              <b-nav-item>
                <router-link to="/services">Services</router-link>
              </b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  /* color: var(--main-color); */
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
