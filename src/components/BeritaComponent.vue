<template lang="">
  <q-layout class="text-center">
    <div class="q-pt-xl">
      <div>
        <h1 class="title">Berita Terbaru</h1>
        <p class="subtitle">
          Ikuti terus informasi dan berita-berita terbaru tentang
          <span>SMK Telkom Makassar</span>.
        </p>
      </div>
      <div
        class="q-pa-md"
        style="display: flex; justify-content: center; flex-wrap: wrap"
      >
        <q-card flat style="width: 300px">
          <q-card-section style="text-align: left">
            <img
              src="img/1699862679-peraih-prestasi-pada-senin-juara.jpeg"
              alt=""
              style="width: 250px"
            />
            <div
              class="text-subtitle2"
              style="color: #777777; margin-top: 10px"
            >
              13 November 2023 | By Admin Telkom
            </div>
            <div class="text-h6 q-my-sm">PERAIH PRESTASI PADA SENIN JUARA</div>
            <div
              class="text-subtitle2 q-pt-sm"
              style="border-top: 1px solid rgba(0, 0, 0, 0.1); color: #777777"
            >
              Baca Selengkapnya
            </div>
          </q-card-section>
        </q-card>
        <q-card flat style="width: 300px">
          <q-card-section style="text-align: left">
            <img
              src="img/1697597318-sosialisasi-keselamatan-berkendara.jpg"
              alt=""
              style="width: 250px"
            />
            <div
              class="text-subtitle2"
              style="color: #777777; margin-top: 10px"
            >
              6 November 2023 | By Admin Telkom
            </div>
            <div class="text-h6 q-my-sm">SENIN DENGAN SEGUDANG PRESTASI</div>
            <div
              class="text-subtitle2 q-pt-sm"
              style="border-top: 1px solid rgba(0, 0, 0, 0.1); color: #777777"
            >
              Baca Selengkapnya
            </div>
          </q-card-section>
        </q-card>
        <q-card flat style="width: 300px">
          <q-card-section style="text-align: left">
            <img
              src="img/1698551312-job-fair-with-stelk-my-career-is-my-hand.jpg"
              alt=""
              style="width: 250px"
            />
            <div
              class="text-subtitle2"
              style="color: #777777; margin-top: 10px"
            >
              28 October 2023 | By Admin Telkom
            </div>
            <div class="text-h6 q-my-sm">
              JOB FAIR WITH STELK: MY CAREER IS MY HAND
            </div>
            <div
              class="text-subtitle2 q-pt-sm"
              style="border-top: 1px solid rgba(0, 0, 0, 0.1); color: #777777"
            >
              Baca Selengkapnya
            </div>
          </q-card-section>
        </q-card>
        <q-card flat style="width: 300px">
          <q-card-section style="text-align: left">
            <img
              src="img/1699349614-senin-dengan-segudang-prestasi.jpeg"
              alt=""
              style="width: 250px"
            />
            <div
              class="text-subtitle2"
              style="color: #777777; margin-top: 10px"
            >
              16 October 2023 | By Admin Telkom
            </div>
            <div class="text-h6 q-my-sm">
              Sosialisasi Keselamatan Berkendara
            </div>
            <div
              class="text-subtitle2 q-pt-sm"
              style="border-top: 1px solid rgba(0, 0, 0, 0.1); color: #777777"
            >
              Baca Selengkapnya
            </div>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </q-layout>
</template>
<script>
export default {};
</script>
<style scoped>
.title {
  font-weight: bold;
  font-size: 40px;
  margin: 0 0 10px 0;
  line-height: normal;
}

.subtitle {
  color: #777777;
}

span {
  color: #bd2130;
}

.text-h6 {
  cursor: pointer;
  transition: 0.3s ease;
}
.text-h6:hover {
  color: #bd2130;
}

.q-card {
  cursor: pointer;
}

img {
  transition: 0.3s ease;
}
img:hover {
  transform: scale(1.05);
}
</style>
