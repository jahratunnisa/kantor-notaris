<template>
    <div class="container-fluid bg-dark py-5 text-white">
      <div class="row justify-content-center mb-5 px-3">
        <div class="col-12 col-md-6">
          <div class="card bg-white bg-opacity-10 text-white rounded-4 border-0 shadow-lg text-center p-4" style="backdrop-filter: blur(5px);">
            <h4 class="mb-0">
              <i class="bi bi-people-fill me-2"></i>
              Jumlah Karyawan: <strong>12 Orang</strong>
            </h4>
          </div>
        </div>
      </div>
  
      <div class="row justify-content-center g-4 px-3 px-md-5">
        <div class="col-12 col-md-4 col-lg-3">
          <div class="img-card-portrait card p-0 rounded-4 overflow-hidden mx-auto shadow-lg">
            <img src="../../assets/img/kar1.jpeg" class="img-fluid img-full" alt="Foto 1" />
          </div>
        </div>
        <div class="col-12 col-md-4 col-lg-3">
          <div class="img-card-portrait card p-0 rounded-4 overflow-hidden mx-auto shadow-lg">
            <img src="../../assets/img/kar1.jpeg" class="img-fluid img-full" alt="Foto 2" />
          </div>
        </div>
      </div>
  
      <div class="row justify-content-center g-4 mt-4 px-3 px-md-5">
        <div class="col-12 col-md-8 col-lg-6">
          <div class="img-card-landscape card p-0 rounded-4 overflow-hidden mx-auto shadow-lg">
            <img src="../../assets/img/kar2.jpeg" class="img-fluid img-full" alt="Foto 3" />
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .img-full {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .img-card-portrait {
    max-width: 250px;
    height: 330px;
  }
  
  .img-card-landscape {
    width: 100%;
    max-width: 600px;
    aspect-ratio: 16 / 9;
  }
  
  .img-card-portrait:hover .img-full,
  .img-card-landscape:hover .img-full {
    transform: scale(1.03);
    box-shadow: 0 10px 20px rgba(255, 255, 255, 0.15);
  }
  </style>
  