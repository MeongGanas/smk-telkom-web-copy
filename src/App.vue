<template lang="">
  <q-layout>
    <q-header class="bayangan text-dark fixed">
      <q-toolbar class="q-pa-md q-px-xl fixed-top">
        <q-img src="img/logo_pcpqhr.png" width="40px" />
        <q-space />
        <q-btn
          flat
          @click="leftDrawerOpen = !leftDrawerOpen"
          round
          dense
          icon="menu"
          class="text-white lt-sm"
        />
        <div class="gt-sm">
          <q-btn
            label="BERANDA"
            flat
            rounded
            color="white"
            class="nav-item"
            icon-right="expand_more"
          >
            <q-menu transition-show="scale" transition-hide="scale">
              <q-list dense padding>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Sambutan Kepala Sekolah</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Profile Sekolah</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm">Acara</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Galeri Sekolah</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >iGracias for TS</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm">Downloads</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
          <q-btn
            label="TENTANG KAMI"
            flat
            rounded
            color="white"
            class="nav-item"
            icon-right="expand_more"
          >
            <q-menu transition-show="scale" transition-hide="scale">
              <q-list dense padding>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Profil Sekolah</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm">Visi & Misi</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Struktur Organisasi</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm">Akreditasi</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Hubungan Industri</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Program Pendidikan CCP</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm"
                    >Program TS 2.1</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm">Fasilitas</q-item-section>
                </q-item>
                <q-item clickable>
                  <q-item-section class="q-pa-sm">Prestasi</q-item-section>
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
          <q-btn
            label="PROGRAM"
            flat
            rounded
            color="white"
            class="nav-item"
            icon-right="expand_more"
          >
            <q-menu transition-show="scale" transition-hide="scale">
              <q-list dense padding>
                <q-item clickable>
                  <q-item-section label class="q-pa-sm"
                    >Profil Jurusan</q-item-section
                  >
                </q-item>
                <q-item clickable>
                  <q-item-section label class="q-pa-sm"
                    >Ekstrakurikuler</q-item-section
                  >
                </q-item>
              </q-list>
            </q-menu>
          </q-btn>
          <q-btn
            label="ALUMNI"
            flat
            rounded
            color="white"
            class="nav-item"
            icon-right="expand_more"
          >
          </q-btn>
          <q-btn
            label="HUBUNGI KAMI"
            flat
            rounded
            color="white"
            class="nav-item"
            icon-right="expand_more"
          >
          </q-btn>
          <q-btn label="PERISAI" flat rounded color="white" class="nav-item">
          </q-btn>
        </div>
      </q-toolbar>
    </q-header>

    <q-drawer
      v-model="leftDrawerOpen"
      side="left"
      bordered
      class="q-pa-md text-white lt-sm"
      style="background: rgba(0, 0, 0)"
    >
      <q-list>
        <q-expansion-item expand-separator label="BERANDA" class="bold">
          <q-list dense padding>
            <q-item clickable>
              <q-item-section class="q-pa-sm"
                >Sambutan Kepala Sekolah</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Profile Sekolah</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Acara</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Galeri Sekolah</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">iGracias for TS</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Downloads</q-item-section>
            </q-item>
          </q-list>
        </q-expansion-item>
        <q-expansion-item expand-separator label="TENTANG KAMI" class="bold">
          <q-list dense padding>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Profil Sekolah</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Visi & Misi</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm"
                >Struktur Organisasi</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Akreditasi</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Hubungan Industri</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm"
                >Program Pendidikan CCP</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Program TS 2.1</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Fasilitas</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section class="q-pa-sm">Prestasi</q-item-section>
            </q-item>
          </q-list>
        </q-expansion-item>
        <q-expansion-item expand-separator label="PROGRAM" class="bold">
          <q-list dense padding>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Profil Jurusan</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Ekstrakurikuler</q-item-section
              >
            </q-item>
          </q-list>
        </q-expansion-item>
        <q-expansion-item expand-separator label="ALUMNI" class="bold">
          <q-list dense padding>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Profil Alumni</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Testimoni Alumni</q-item-section
              >
            </q-item>
          </q-list>
        </q-expansion-item>
        <q-expansion-item expand-separator label="HUBUNGI KAMI" class="bold">
          <q-list dense padding>
            <q-item clickable>
              <q-item-section label class="q-pa-sm">FAQs</q-item-section>
            </q-item>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Pusat Bantuan</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Kotak Pertanyaan</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Saran Orang Tua / Wali Siswa</q-item-section
              >
            </q-item>
            <q-item clickable>
              <q-item-section label class="q-pa-sm"
                >Pusat Bantuan</q-item-section
              >
            </q-item>
          </q-list>
        </q-expansion-item>
        <q-item clickable>
          <q-item-section label>PERISAI</q-item-section>
        </q-item>
      </q-list>
    </q-drawer>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>
<script>
import { ref } from "vue";
export default {
  setup() {
    const leftDrawerOpen = ref(false);

    return {
      leftDrawerOpen,
      toggleLeftDrawer() {
        leftDrawerOpen.value = !leftDrawerOpen.value;
      },
    };
  },
  data() {
    return {
      scrollY: 0,
    };
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      this.scrollY = window.scrollY;

      if (this.scrollY > 0) {
        document.querySelector(".q-toolbar").classList.add("bg-dark");
      } else {
        document.querySelector(".q-toolbar").classList.remove("bg-dark");
      }
    },
  },
};
</script>
<style scoped>
.nav-item {
  font-size: 12px;
}
</style>
