<template lang="">
  <q-layout class="text-center">
    <div
      class="q-py-xl"
      style="
        background: #efefef;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        flex-wrap: wrap;
      "
    >
      <div style="width: 60%">
        <h1 class="title" style="color: #bd2130">Ayo gabung bersama kami.</h1>
      </div>
      <div style="width: 40%">
        <img src="img/perisai_ao9ugl.png" alt="" width="200" />
      </div>
    </div>
    <div class="q-py-xl q-px-xl" style="background: #04091e">
      <div
        style="
          display: flex;
          justify-content: space-around;
          color: white;
          flex-wrap: wrap;
        "
      >
        <div class="menu-utama" style="width: 380px">
          <h1 class="text-h6" style="text-align: left">Menu Utama</h1>
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >Beranda</router-link
          >
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >Tentang Kami</router-link
          >
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >Profil Jurusan</router-link
          >
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >Perisai</router-link
          >
        </div>
        <div class="hubungi-kami" style="width: 380px">
          <h1 class="text-h6" style="text-align: left">Hubungi Kami</h1>
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >FAQ</router-link
          >
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >Layanan Orang Tua</router-link
          >
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >Kontak Pertanyaan</router-link
          >
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >Pusat Bantuan</router-link
          >
        </div>
        <div class="useful-links" style="width: 380px">
          <h1 class="text-h6" style="text-align: left">Useful Links</h1>
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >iGracias TS</router-link
          >
          <router-link
            to="#"
            style="
              display: block;
              text-align: left;
              margin-bottom: 10px;
              text-decoration: none;
              color: #777777;
            "
            >YPT</router-link
          >
        </div>
      </div>
      <div class="">
        <h1
          class="text-subtitle1 q-mt-xl"
          style="color: #777777; text-align: left"
        >
          Copyright
          <span style="color: #bd2130">SMK Telkom Makassar</span> @2023.
        </h1>
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

router-link:hover {
  color: #bd2130;
}
</style>
