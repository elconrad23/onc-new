<script lang="ts">
  import { onMount } from 'svelte';
  import Hls from 'hls.js';

  export let link;
  let videoElement;

  onMount(async () => {
    if (Hls.isSupported()) {
      const hls = new Hls();
      hls.loadSource(link);
      hls.attachMedia(videoElement);
    } else if (videoElement.canPlayType('application/vnd.apple.mpegurl')) {
      videoElement.src = link;
    }
  });
</script>

<style>
  @import 'video.js/dist/video-js.css';

  #my-video{
    width: 63em;
    height: auto;
  }

</style>

<div>
  <video class="video-js" controls id="my-video" preload="auto" bind:this={videoElement}>
    <source src="{link}" type="application/x-mpegURL">
    <track kind="captions" label="English Captions" src="" default>
    <!-- Add additional sources for different formats if desired -->
  </video>
</div>
