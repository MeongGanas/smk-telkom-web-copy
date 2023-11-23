<template lang="">
  <q-section class="text-center" style="overflow: hidden">
    <div class="q-pt-xl">
      <div class="q-mb-xl">
        <h1 class="title">Kenapa Harus <span>SMK Telkom Makassar</span>?</h1>
        <p class="subtitle">
          Alasan kenapa harus memilih untuk bergabung dengan
          <span>SMK Telkom Makassar</span>
        </p>
      </div>

      <div class="alasan" style="overflow-x: auto">
        <q-infinite-scroll @load="onLoad" :offset="250" style="display: flex">
          <div v-for="(item, index) in items" :key="index">
            <div class="slider" style="display: flex; justify-content: center">
              <q-card flat style="width: 310px; height: 300px">
                <div class="card">
                  <q-card-section>
                    <img
                      src="img/icons/laptop_ksosxp.png"
                      alt=""
                      style="width: 100px"
                    />
                    <div class="text-h6">Fasilitas Lengkap</div>
                    <div class="text-subtitle2 q-mt-md">
                      Penunjang belajar dengan kualitas premium.
                    </div>
                  </q-card-section>
                </div>
              </q-card>
              <q-card flat style="width: 310px; height: 300px">
                <div class="card">
                  <q-card-section>
                    <img
                      src="img/icons/school_jfslqk.png"
                      alt=""
                      style="width: 100px"
                    />
                    <div class="text-h6">Lingkungan Nyaman</div>
                    <div class="text-subtitle2 q-mt-md">
                      Berada di lingkungan asri, aman, dan kondusif.
                    </div>
                  </q-card-section>
                </div>
              </q-card>
              <q-card flat style="width: 310px; height: 300px">
                <div class="card">
                  <q-card-section>
                    <img
                      src="img/icons/presentation_dai7nn.png"
                      alt=""
                      style="width: 100px"
                    />
                    <div class="text-h6">Pengajar Kompeten</div>
                    <div class="text-subtitle2 q-mt-md">
                      Guru yang up-to-date dengan perkembangan industri
                    </div>
                  </q-card-section>
                </div>
              </q-card>
              <q-card flat style="width: 310px; height: 300px">
                <div class="card">
                  <q-card-section>
                    <img
                      src="img/icons/team_lxvtyk.png"
                      alt=""
                      style="width: 100px"
                    />
                    <div class="text-h6">Kerjasama Luas</div>
                    <div class="text-subtitle2 q-mt-md">
                      Memperbesar kesempatan bekerja sebelum lulus.
                    </div>
                  </q-card-section>
                </div>
              </q-card>
            </div>
          </div>
          <template v-slot:loading>
            <div class="row justify-center q-my-md">
              <q-spinner-dots color="primary" size="40px" />
            </div>
          </template>
        </q-infinite-scroll>
      </div>
    </div>
  </q-section>
</template>
<script>
import { ref } from "vue";
export default {
  setup() {
    const items = ref([{}, {}, {}, {}]);

    return {
      items,
      onLoad(index, done) {
        setTimeout(() => {
          items.value.push({}, {}, {}, {});
          done();
        }, 2000);
      },
    };
  },
};
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

.text-h6 {
  margin-top: 10px;
  transition: 0.3s ease;
}

.alasan::-webkit-scrollbar {
  display: none;
}
.card:hover .text-h6 {
  color: #bd2130;
}

span {
  color: #bd2130;
}

img {
  transition: 0.3s ease;
}
img:hover {
  transform: scale(1.2);
}

.slider {
  position: relative;
  animation: slider 60s infinite;
}

@keyframes slider {
  0% {
    transform: translateX(0);
  }
  5% {
    transform: translateX(0);
  }
  10% {
    transform: translateX(-310px);
  }
  15% {
    transform: translateX(-310px);
  }
  20% {
    transform: translateX(-620px);
  }
  25% {
    transform: translateX(-620px);
  }
  30% {
    transform: translateX(-930px);
  }
  35% {
    transform: translateX(-930px);
  }
  40% {
    transform: translateX(-1240px);
  }
  45% {
    transform: translateX(-1240px);
  }
  50% {
    transform: translateX(-1550px);
  }
  55% {
    transform: translateX(-1550px);
  }
  60% {
    transform: translateX(-1860px);
  }
  65% {
    transform: translateX(-1860px);
  }
  70% {
    transform: translateX(-2170px);
  }
  75% {
    transform: translateX(-2170px);
  }
  80% {
    transform: translateX(-2480px);
  }
  85% {
    transform: translateX(-2480px);
  }
  90% {
    transform: translateX(-2790px);
  }
  95% {
    transform: translateX(-2790px);
  }
  100% {
    transform: translateX(0);
  }
}
</style>
