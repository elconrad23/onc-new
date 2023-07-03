
<Player controls autoplay muted ref={player} currentTime={currentTime}
  on:vmCurrentTimeChange={onTimeUpdate}
  on:vmFullscreenChange={onFullscreenChange} >

  <!-- Provider component is placed here. -->
  <Hls version="latest" config="{hlsConfig}" poster="/lib/images/omalako.jpeg">
    <source data-src="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_Bukomansimbi_vod_nm/20/vod.m3u8"
     type="application/x-mpegURL" />
  </Hls>
  <Ui><!-- UI components are placed here. --></Ui>
</Player>

<script lang="ts">
    import { Player, Hls, Ui, usePlayerStore } from '@vime/svelte';
  
    let player;
    let currentTime = 0;
    const hlsConfig = {
    // ...
    };
    // OPTIONAL: If you prefer you can use the player store.
    const { paused } = usePlayerStore(player);
    $paused = false;
    $: console.log($paused);
  
    // Example function to showcase updating property.
    const seekForward = () => {
      currentTime += 5;
    };
  
    // Example function to showcase calling player method.
    const enterFullscreen = () => {
      player.enterFullscreen();
    };
  
    const onTimeUpdate = (event) => {
      currentTime = event.detail;
    };
  
    const onFullscreenChange = (event) => {
      const isFullscreen = event.detail;
      // ...
    };
  </script>