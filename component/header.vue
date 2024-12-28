<template>
  <div class="row align-items-center p-3 bg-primary text-white">
    <!-- Logo -->
    <div class="img col-lg-1 text-center">
      <img src="~/assets/img/logo.png" alt="logo smk" class="logo" />
    </div>

    <!-- Navbar -->
    <div class="col-lg-11 d-flex justify-content-between align-items-center">
      <!-- Nama Sekolah -->
      <div>
        <h1 class="school-name">SMKN 4 TASIKMALAYA</h1>
        <p class="school-tagline">Cerdas, Beriman, Berkarakter</p>
      </div>

      <!-- Navbar -->
      <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
              <!-- Dropdown Beranda -->
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="berandaDropdown"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Beranda
                </a>
                <ul class="dropdown-menu" aria-labelledby="berandaDropdown">
                  <li><a class="dropdown-item" href="#">Berita</a></li>
                  <li><a class="dropdown-item" href="#">Gallery</a></li>
                  <li><a class="dropdown-item" href="#">Prestasi</a></li>
                </ul>
              </li>

              <!-- Dropdown Profil -->
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="profilDropdown"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Profil
                </a>
                <ul class="dropdown-menu" aria-labelledby="profilDropdown">
                  <li><a class="dropdown-item" href="#">Visi dan Misi</a></li>
                  <li><a class="dropdown-item" href="#">Kepala Sekolah</a></li>
                </ul>
              </li>

              <!-- Dropdown Data -->
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  id="dataDropdown"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Data
                </a>
                <ul class="dropdown-menu" aria-labelledby="dataDropdown">
                  <li><a class="dropdown-item" href="#">Guru</a></li>
                </ul>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<style scoped>
/* Styling utama */
.row {
  margin: 0;
}

/* Logo */
.img .logo {
  max-width: 100%;
  height: auto;
  max-height: 70px;
}

/* Nama Sekolah */
.school-name {
  font-size: 1.8rem;
  font-weight: bold;
  margin: 0;
  line-height: 1.2;
}

.school-tagline {
  font-size: 1rem;
  margin: 0;
  font-style: italic;
  color: #e0e0e0;
}

/* Navbar */
.navbar {
  padding: 0;
}

.navbar-nav .nav-item .nav-link {
  color: white;
}

.navbar-nav .dropdown-menu {
  background-color: white;
  border-radius: 0.25rem;
}

.navbar-nav .dropdown-menu .dropdown-item {
  color: black;
}

.navbar-nav .dropdown-menu .dropdown-item:hover {
  background-color: #f8f9fa;
}
</style>