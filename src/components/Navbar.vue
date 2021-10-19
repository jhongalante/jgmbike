<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
      <div class="container">
        <a class="navbar-brand" href="#"
          ><i class="fas fa-bicycle"></i> JGM Bike</a
        >
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Alterna navegação"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link">Home</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >
                Produtos
              </a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <a href="#">Teste</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Todos os produtos</a>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link">Serviços</a>
            </li>
            <li class="nav-item">
              <a class="nav-link">Sobre</a>
            </li>
            <li class="nav-item">
              <a class="nav-link">Contato</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>