<template>
  <nav class="site-navbar navbar navbar-expand-md navbar-dark bg-dark py-3">
    <router-link class="navbar-brand d-flex flex-row align-items-center text-uppercase" to="/" exact>
      <img class="mr-2" src="/images/logo.png" width="36" height="36">
      <span>Portal Pemerintah Provinsi Banten</span>
    </router-link>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar" aria-controls="navbar" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbar">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-link class="nav-link" to="/dashboard" exact>Dashboard</router-link>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
           Dropdown
          </a>
          <div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbarDropdown">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </li>
      </ul>
    </div>
  </nav>
</template>
