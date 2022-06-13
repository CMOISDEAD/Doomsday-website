<template>
  <div class="navbar gradient-border-bottom">
    <div class="logo">Doomsday</div>
    <ul class="nav-links">
      <li><a href="#features">Features</a></li>
      <li><a href="#preview">Preview</a></li>
      <li><a href="#download">Download</a></li>
      <li><a href="#about">About us</a></li>
    </ul>
  </div>
</template>

<style>
.navbar {
  padding: 2vh;
  margin: 0 1vw;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.nav-links {
  display: flex;
}

.logo {
  font-size: 1.3rem;
  font-weight: bold;
}

li {
  list-style: none;
  padding: 0 1vw;
}

a {
  padding: 0.4rem;
  border-radius: 0.5rem;
  text-decoration: none;
}

@media (max-width: 565px) {
  .navbar {
    justify-content: center;
  }
  .logo {
    text-align: center;
  }
  .nav-links {
    display: none;
  }
}
</style>
