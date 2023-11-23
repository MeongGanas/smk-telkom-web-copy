<template lang="">
  <q-page>
    <HomeComponent
      title="THE REAL INFORMATICS SCHOOL"
      subtitle="Pelopor SMK bidang Teknologi Informasi dan Komunikasi di Indonesia."
      img="img/DSCF8979_jtyuim.jpg"
    />
  </q-page>
  <q-page style="min-height: 100vh; display: flex; align-items: center">
    <WhyComponent />
  </q-page>
  <q-page style="min-height: fit-content">
    <SalamComponent />
  </q-page>
  <q-page style="min-height: 100vh">
    <ProgramComponent />
  </q-page>
  <q-page style="min-height: fit-content">
    <BeritaComponent />
  </q-page>
  <q-page style="min-height: fit-content">
    <FooterComponent />
  </q-page>
</template>
<script>
import HomeComponent from "@/components/HomeComponent.vue";
import WhyComponent from "@/components/WhyComponent.vue";
import SalamComponent from "@/components/SalamComponent.vue";
import ProgramComponent from "@/components/ProgramComponent.vue";
import BeritaComponent from "@/components/BeritaComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue";
export default {
  components: {
    HomeComponent,
    WhyComponent,
    SalamComponent,
    ProgramComponent,
    BeritaComponent,
    FooterComponent,
  },
};
</script>
<style lang=""></style>
