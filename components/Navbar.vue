<template>
  <nav class="navbar navbar-expand-lg bg-secondary">
    <div class="container-fluid">
      <img src="~/assets/LOGO-SMK4.png" alt="" width="50px" height="50px" class="d-inline-block align-text-top">
      <h4 class="navbar-brand d-flex" href="#">SMKN 4 TASIKMALAYA</h4>
      <h6>jl.depok,sukamenak,purbaratu</h6>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll"
        aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarScroll">
        <ul class="navbar-nav ms-auto me-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Galeri</a>
          </li>

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
           Profile
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">identitas sekolah</a></li>
              <li><a class="dropdown-item" href="#">sejarah</a></li>
              <li><a class="dropdown-item" href="#">visi misi</a></li>
              <li><a class="dropdown-item" href="#">identitas kepala sekolah</a></li>
              <li><a class="dropdown-item" href="#">struktur organisasi</a></li>
              <li><a class="dropdown-item" href="#">Guru&staf</a></li>
            </ul>
          </li>


          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Ekstrakulikuler
            </a>
            <ul class="dropdown-menu">
              <li><a class="dropdown-item" href="#">Pramuka</a></li>
              <li><a class="dropdown-item" href="#">Pmr</a></li>
              <li><a class="dropdown-item" href="#">Silat</a></li>
              <li><a class="dropdown-item" href="#">Voly</a></li>
              <li><a class="dropdown-item" href="#">Futsal</a></li>
              <li><a class="dropdown-item" href="#">Basket</a></li>
              <li><a class="dropdown-item" href="#">Seni</a></li>
              <li><a class="dropdown-item" href="#">sepakbola</a></li>
              <li><a class="dropdown-item" href="#">English club</a></li>
              <li><a class="dropdown-item" href="#">Rohis</a></li>
            </ul>
          </li>

          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Konsentrasi Keahlian
            </a>
            <ul class="dropdown-menu text-black">
              <li><a class="dropdown-item" href="#">TJKT</a></li>
              <li><a class="dropdown-item" href="#">PPLG</a></li>
              <li><a class="dropdown-item" href="#">TBSM</a></li>
              <li><a class="dropdown-item" href="#">DKV</a></li>
              <li><a class="dropdown-item" href="#">TOI</a></li>
            </ul>
          </li>
              
          <li class="nav-item">
            <a class="nav-link disabled" aria-disabled="true">Berita</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style>
h4, address, .nav-link {
  color: white !important;
}

img {
  width: 50px;
}
</style>