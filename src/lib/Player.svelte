


<script lang="ts">
  import { onMount } from 'svelte';
  import videojs from "video.js";

  let link = "https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_WestNile_vod_px/20/vod.m3u8";

  onMount( async () => {
    await videojs('my-video');
  });

</script>

<style>
  @import 'video.js/dist/video-js.css';
</style>

<div>
  <video class="video-js" controls id="my-video" preload="auto" style="width:100%; height:auto;">
    <source src="{link}" type="application/x-mpegURL">
      <track kind="captions"/>
    <!-- Add additional sources for different formats if desired -->
  </video>
</div>