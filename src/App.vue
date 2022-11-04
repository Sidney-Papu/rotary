<template>

  <nav class="navbar navbar-expand-lg" style="background-color: violet;">
    <div class="container-fluid">
      <!-- <a class="navbar-brand" href="#">Rotary Taquaritinga</a>-->
      <img :src="require('./assets/rotary_topo.png')" />
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <router-link to="/Home">Início</router-link> |
          </li>
          <li class="nav-item">
            <router-link to='/equipamentos'>Equipamentos</router-link> |
          </li>
          <li class="nav-item">
            <router-link to="/about">Sobre</router-link> |
          </li>
          <li class="nav-item">
            <router-link to="/Contato">Contato</router-link> |
          </li>
          <li class="nav-item">
            <router-link to="/Entrar">Entrar</router-link> |
          </li>
          <li class="nav-item">
            <router-link to="/Cadastro">Cadastro</router-link> |
          </li>
          <li class="nav-item">
            <router-link to="/Admin">Admin</router-link>
          </li>
        </ul>
        <!-- <a class="navbar-brand" href="#">Imagine o Rotary</a>-->
        <img :src="require('./assets/imagine_2.png')" />
        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Pesquisa" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Pesquisa</button>
        </form>
      </div>
    </div>
  </nav>






  <router-view />
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
  color: #e2e5e9;
  text-decoration: none;
  padding: 10px 10px;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

<script>

</script>