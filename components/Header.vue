<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-danger sticky-top custom-navbar">
    <div class="container-fluid">
      <a class="navbar-brand d-flex justify-content-start" href="#">
        <img src="../assets/img/logo1.png" alt="Logo" width="70" class="logo-shadow me-2" />
        <div>
          <div class="fw-bold">Kantor Notaris dan PPAT</div>
          <div style="font-size: 0.9rem">Ida Aryani, SH</div>
        </div>
      </a>
      <div class="px-4">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/">Home</NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink class="nav-link" to="/galeri">Galeri</NuxtLink>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
            >
              Profil
            </a>
            <ul class="dropdown-menu dropdown-menu-end">
              <li>
                <NuxtLink class="dropdown-item" to="/profil/sejarah">Sejarah</NuxtLink>
              </li>
              <li>
                <NuxtLink class="dropdown-item" to="/profil/layanan">Layanan Kami</NuxtLink>
              </li>
              <li>
                <NuxtLink class="dropdown-item" to="/profil/tentang">Tentang Kami</NuxtLink>
              </li>
              <li>
                <NuxtLink class="dropdown-item" to="/profil/alamat">Alamat</NuxtLink>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.custom-navbar {
  z-index: 1050; 
}

.logo-shadow {
  filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.6));
}
</style>
