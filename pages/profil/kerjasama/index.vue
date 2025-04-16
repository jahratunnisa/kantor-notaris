<template>
  <div class="container-fluid bg-dark text-light py-5 ">
    <h2 class="text-center mb-4">Bekerja Sama Dengan</h2>
    <div class="d-flex justify-content-center">
    <div
      class="card bg-white bg-opacity-10 text-light shadow rounded-4 border-0 p-5 kerja-sama-card"
      style="backdrop-filter: blur(6px)"
    >
      <ul class="list-unstyled mb-0">
        <li class="d-flex align-items-center mb-3">
          <img src="../../../assets/img/bank8.png" class="logo-bank me-3" />
          <span>PT BANK MANDIRI (PERSERO) Tbk</span>
        </li>
        <li class="d-flex align-items-center mb-3">
          <img src="../../../assets/img/bank7.png" class="logo-bank me-3" />
          <span>PT BANK SYARI'AH INDONESIA</span>
        </li>
        <li class="d-flex align-items-center mb-3">
          <img src="../../../assets/img/bank6.png" class="logo-bank me-3" />
          <span>PT BANK CENTRAL ASIA</span>
        </li>
        <li class="d-flex align-items-center mb-3">
          <img src="../../../assets/img/bank5.png" class="logo-bank me-3" />
          <span>PT BANK NEGARA INDONESIA</span>
        </li>
        <li class="d-flex align-items-center mb-3">
          <img src="../../../assets/img/bank4.png" class="logo-bank me-3" />
          <span>PT BANK SINARMAS</span>
        </li>
        <li class="d-flex align-items-center mb-3">
          <img src="../../../assets/img/bank3.png" class="logo-bank me-3" />
          <span>PT PEMODALAN NASIONAL MADANI</span>
        </li>
        <li class="d-flex align-items-center mb-3">
          <img src="../../../assets/img/bank2.png" class="logo-bank me-3" />
          <span>PT BANK CIMB NIAGA TBK</span>
        </li>
        <li class="d-flex align-items-center">
          <img src="../../../assets/img/bank1.png" class="logo-bank me-3" />
          <span>PT BANK OCBC NISP TBK</span>
        </li>
      </ul>
    </div>
</div>
    <div class="row">
      <div class="col text-end mt-4 px-5">
        <NuxtLink to="/profil/layanan" class="text-light text-decoration-none">
          <div><i class="bi bi-arrow-left-circle-fill"></i> Kembali</div>
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<style scoped>
.kerja-sama-card {
  width: 800px;
}

.logo-bank {
  width: 60px;
  height: auto;
  object-fit: contain;
}
</style>
