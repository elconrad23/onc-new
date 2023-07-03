<svelte:head>
	<title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS." />
    <!-- Default theme. ~960B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/default.css"/>

    <!-- Optional light theme (extends default). ~400B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/light.css" />

</svelte:head>
<script>
    // import Player from "$lib/Player.svelte";
    import HlsPlayer from "$lib/HlsPlayer.svelte";
</script>

<div class="grid">
    <hgroup>
        <h2> West Nile today</h2>
        <!--
        <Player/>
        -->
        <HlsPlayer link="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_WestNile_vod_px/20/vod.m3u8" />
        <p>This Content is licensed and distributed exclusively by Ready Media.</p>
        <br/>

 </hgroup>  
    <aside>

        <h4> About the West Nile.</h4>
        <p>
            The sub-region is bordered by the Democratic Republic of the Congo to the south and west, by South Sudan to the north and by the Albert Nile to the east. The town of Arua, is the largest town in the sub-region. Arua lies approximately 475 kilometres (295 mi), by road, northwest of Kampala, the capital of Uganda, and the largest city in that country.    
        </p>
        <p><small>What's happening in: </small></p> 
        <a href="/Buko_media">Bukomansimbi</a><br>
        <a href="/Bika_media">Bika bya Buganda</a><br>
        <a href="https://www.youtube.com/@onc_nrm">Tap here for the ONC youtube Channel</a><br/>
        </aside>
</div>

<style>
    h2{
        text-align: center;
    }

    .grid{
        text-align: center;
        display: flex;
        position: middle;
        flex-direction: column;
        align-items: center;
    }
</style>