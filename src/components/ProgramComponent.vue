<template lang="">
  <q-layout class="text-center">
    <div class="q-pt-xl">
      <div>
        <h1 class="title">Program Keahlian</h1>
        <p class="subtitle">
          Pilihan program keahlian di <span>SMK Telkom Makassar</span>.
        </p>
      </div>
      <div style="display: flex; justify-content: center">
        <div
          class="q-pa-md"
          style="
            width: 80%;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
          "
        >
          <q-card flat style="width: 300px; height: 200px">
            <div class="card">
              <q-card-section>
                <img
                  src="img/icons/signal-tower_iih61g.png"
                  alt=""
                  style="width: 100px"
                />
                <div class="text-h6">Teknik Transmisi Telekomunikasi</div>
              </q-card-section>
            </div>
          </q-card>
          <q-card flat style="width: 300px; height: 200px">
            <div class="card">
              <q-card-section>
                <img
                  src="img/icons/desktop_wojbbe.png"
                  alt=""
                  style="width: 100px"
                />
                <div class="text-h6">Teknik Komputer dan Jaringan</div>
              </q-card-section>
            </div>
          </q-card>
          <q-card flat style="width: 300px; height: 200px">
            <div class="card">
              <q-card-section>
                <img
                  src="img/icons/computer_smrpjc.png"
                  alt=""
                  style="width: 100px"
                />
                <div class="text-h6">Teknik Jaringan Akses Komunikasi</div>
              </q-card-section>
            </div>
          </q-card>
          <q-card flat style="width: 300px; height: 200px">
            <div class="card">
              <q-card-section>
                <img
                  src="img/icons/laptop_ksosxp.png"
                  alt=""
                  style="width: 100px"
                />
                <div class="text-h6">Rekayasa Perangkat Lunak</div>
              </q-card-section>
            </div>
          </q-card>
          <q-card flat style="width: 300px; height: 200px">
            <div class="card">
              <q-card-section>
                <img
                  src="img/icons/passport_qsoz1f.png"
                  alt=""
                  style="width: 100px"
                />
                <div class="text-h6">Usaha Perjalanan Wisata</div>
              </q-card-section>
            </div>
          </q-card>
          <q-card flat style="width: 300px; height: 200px">
            <div class="card">
              <q-card-section>
                <img
                  src="img/icons/hotel_o1seyq.png"
                  alt=""
                  style="width: 100px"
                />
                <div class="text-h6">Perhotelan</div>
              </q-card-section>
            </div>
          </q-card>
        </div>
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
  color: grey;
}

span {
  color: #bd2130;
}

.card {
  transition: 0.3s ease;
}
.card:hover {
  color: #bd2130;
}

img {
  transition: 0.3s ease;
}
img:hover {
  transform: scale(1.2);
}
</style>
