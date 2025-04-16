<template>
  <div class="container-fluid min-vh-100 py-5">
    <div class="row justify-content-center align-items-start g-4 px-md-5">
      <div class="open col-md-3">
        <div class="card shadow rounded-4 bg-white h-100">
          <div class="card-header bg-danger text-light text-center fs-5 rounded-top-4">
            Opening hours
          </div>
          <div class="card-body text-center">
            <p><strong>Senin - Jumat</strong><br />08.00 - 17.00</p>
            <p><strong>Sabtu</strong><br />08.00 - 12.00</p>
            <p><strong>Minggu</strong><br />Tutup</p>
          </div>
        </div>
      </div>

      <div class="col-md-3 text-center">
        <img
          src="../assets/img/ibu.jpeg"
          alt="Ibu Ida Aryani"
          class="rounded-4 shadow border border-3 border-danger img-fluid mb-3"
        />
        <div class="bg-danger text-light py-2 rounded-3 fs-5 fw-semibold">
          Ibu Ida Aryani S.H
        </div>
      </div>

      <div class="sambutan col-md-3">
        <div class="card shadow rounded-4 bg-white h-100">
          <div class="card-header bg-danger text-light text-center fs-5 rounded-top-4">
            Sambutan
          </div>
          <div class="card-body">
            <p>Assalamualaikum wr.wb</p>
            <p>
              Salam hangat! Selamat datang di website kantor Notaris dan PPAT Ida Aryani
              S.H. Website ini dibuat agar dapat membantu memberikan informasi praktis
              secara online mengenai hal-hal yang berhubungan dengan service Notaris &
              PPAT (Pejabat Pembuat Akta Tanah) dari kantor kami.
            </p>
            <div class="d-flex justify-content-center mt-3">
              <img src="../assets/img/logo.png" alt="Logo 2" class="img-fluid w-75" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-fluid {
  background-image: url("../assets/img/bg.jpeg");
  background-size: cover;
  background-position: center;
}

@media (min-width: 768px) {
  .open {
    padding-top: 35%;
  }
  .sambutan {
    padding-top: 27%;
  }
}

@media (max-width: 767.98px) {
  .open,
  .sambutan {
    padding-top: 0;
  }
}
</style>
