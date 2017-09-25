<template>
  <div id="app">
    <section class="hero is-primary is-bold is-large">
      <div class="hero-head">
        <header class="nav">
          <div class="container">
            <div class="nav-left">
              <a class="nav-item" href="/#/">
                <img src="./assets/img/helloproclub-logo-white-simple.svg">
              </a>
            </div>
            <span class="nav-toggle" data-target="nav-menu_t">
              <span></span>
              <span></span>
              <span></span>
            </span>
            <div class="nav-right nav-menu" id="nav-menu_t">
              <a class="nav-item is-active" href="/#/">
                Halaman Utama
              </a>
            </div>
          </div>
        </header>
      </div>

      <div class="hero-body" style="padding-bottom: 32px">
        <router-view></router-view>
      </div>

      <div class="hero-foot" style="padding: 8px 4px 16px">
        <div class="container">
          &copy; 2017, Proclub.
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  cursor: default
}
</style>
