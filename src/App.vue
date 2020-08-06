<template>
  <div class="app-background">
    <NavBar />

    <router-view />

    <Footer />
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
@import "./assets/styles/main.scss";
.app-background {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  justify-content: space-between;
}
</style>
