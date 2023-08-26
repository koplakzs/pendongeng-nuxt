<template>
  <div id="contact" class="row row-cols-3 gap-4 align-items-center justify-content-evenly">
    <div class="col">
      <h1 class="fw-bold text-center">
        Mari Berkeluh Kelas Mengenai Platform Ini!!
      </h1>
    </div>
    <div class="col">
      <h5 class="fw-bold">Kirim Keluh Kesahmu</h5>
      <form method="post">
        <div class="form-floating mb-3">
          <input type="nama" class="form-control" id="nama" placeholder="Nama Lengkap">
          <label for="nama">Nama Lengkap</label>
        </div>
        <div class="form-floating mb-3">
          <input type="email" class="form-control" id="email" placeholder="Email">
          <label for="email">Email Lengkap</label>
        </div>
        <div class="form-floating mb-3">
          <input type="text" class="form-control" id="subject" placeholder="Subject">
          <label for="subject">Subject</label>
        </div>
        <p class="fw-bold">Ceritakan Keluh Kesahmu Disini</p>
        <div class="form-floating mb-3">
          <textarea class="form-control" placeholder="Keluh Kesah" id="keluh-kesah"></textarea>
          <label for="keluh-kesah">Keluh Kesah</label>
        </div>
        <button type="submit" class="btn btn-primary">Kirim Keluh Kesahmu</button>
      </form>
    </div>
  </div>
</template>
