<template>
  <div class="container-fluid bg-dark min-vh-100">
    <div class="text-white p-4">
      <h2 class="text-center my-5">Layanan Kami</h2>

      <div class="row justify-content-center px-5 g-4">
        <div class="col-md-4">
          <div
            class="card card-hover bg-light bg-opacity-75 text-dark shadow-lg rounded-4 border-0 h-100 p-4 d-flex flex-column align-items-center text-center"
            style="backdrop-filter: blur(5px)"
          >
            <i class="bi bi-journal-text" style="font-size: 4rem; margin-bottom: 1rem"></i>
            <h5 class="mb-3">Layanan Notaris</h5>
            <p>
              Dalam membantu pengurusan legalitas bisnis, mutlak diperlukan akta notaris
              untuk pendirian badan usaha. Jasa notaris dibutuhkan untuk mempersiapkan
              akta pendirian PT / CV serta badan usaha lainnya.
            </p>
          </div>
        </div>

        <div class="col-md-4">
          <div
            class="card card-hover bg-light bg-opacity-75 text-dark shadow-lg rounded-4 border-0 h-100 p-4 d-flex flex-column align-items-center text-center"
            style="backdrop-filter: blur(5px)"
          >
            <i class="bi bi-building" style="font-size: 4rem; margin-bottom: 1rem"></i>
            <h5 class="mb-3">Layanan PPAT</h5>
            <p>
              Kami membantu dalam pembuatan akta tanah, jual beli, hibah, dan peralihan
              hak atas tanah, sesuai dengan peraturan yang berlaku.
            </p>
          </div>
        </div>

        <div class="col-md-4">
          <div
            class="card card-hover bg-light bg-opacity-75 text-dark shadow-lg rounded-4 border-0 h-100 p-4 d-flex flex-column align-items-center text-center"
            style="backdrop-filter: blur(5px)"
          >
            <i class="bi bi-chat-dots" style="font-size: 4rem; margin-bottom: 1rem"></i>
            <h5 class="mb-3">Layanan Konsultasi</h5>
            <p>
              Anda bisa konsultasikan secara Gratis segala permasalahan dalam bidang
              perizinan, bisnis, kontrak, perjanjian, dll yang berhubungan dengan
              Kenotariatan dan PPAT tanpa ada pembatasan masalah.
            </p>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col text-end mt-4 px-5">
          <NuxtLink to="/profil/kerjasama" class="text-light text-decoration-none">
            <div>
              Selengkapnya <i class="bi bi-arrow-right-circle-fill"></i>
            </div>
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card-hover {
  transition: all 0.3s ease;
}

.card-hover:hover {
  transform: translateY(-10px) scale(1.03);
  background-color: rgba(255, 255, 255, 0.15);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
}
</style>