<template>
  <div class="layout container">
    <header class="header">
      <span class="siteName">
      <strong>
        <g-link class="is-size-4" to="/">&#128760;{{ $static.metadata.siteName }}</g-link>
      </strong>
      </span>
      <nav class="nav">
        <g-link class="nav__link" to="/">Home</g-link>
        <g-link class="nav__link" to="/about/">About</g-link>
      </nav>
    </header>
    <slot/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Comfortaa&family=Open+Sans&display=swap');
@import "~/assets/css/_variables.scss";

body {
  font-family: 'Open Sans', sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
}

.siteName {
  font-family: 'Comfortaa', cursive;
}

.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
  height: 80px;
  background-color: $header-background-color;
}

.nav__link {
  margin-left: 20px;
}
</style>
