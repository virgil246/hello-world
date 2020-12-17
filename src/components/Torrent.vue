<template>
  <div class="video">
    <h1>{{ title }}</h1>
    <video ref="videoPlayer" class="video-js"></video>
  </div>
</template>


<script>
// import "video.js/dist/video-js.css";
// import videojs from "video.js";

export default {
  name: "Torrent",
  components: {},
  props: {
    title: String,
    btlink: String,
  },
  setup() {},
};
</script>