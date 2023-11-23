<template lang="">
  <q-layout>
    <q-img
      :src="img"
      class="absolute-top fullscreen"
      style="z-index: -9999"
    ></q-img>
    <div
      class="absolute-top bg-dark fullscreen"
      style="opacity: 0.6; z-index: -9998"
    ></div>
    <div
      class="absolute-top flex items-center justify-center q-pa-md fullscreen"
      style="z-index: 1"
    >
      <div class="text-center">
        <h1 class="title">
          {{ title }}
        </h1>
        <p class="subtitle">{{ subtitle }}</p>
      </div>
    </div>
  </q-layout>
</template>
<script>
export default {
  props: ["title", "subtitle", "img"],
};
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
}

.subtitle {
  color: white;
  margin-top: 10px;
  font-size: 15px;
}

.title {
  color: white;
  margin: 0px;
  padding: 0;
  font-size: 50px;
  font-weight: bold;
  line-height: normal;
}
</style>
