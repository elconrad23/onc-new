
<script>
    import HlsPlayer from "$lib/HlsPlayer.svelte";
</script>

<svelte:head>
	<title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS." />
    <!-- Default theme. ~960B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/default.css"/>

    <!-- Optional light theme (extends default). ~400B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/light.css" />

</svelte:head>

<hgroup>
    <h2> Bukoma Nsimbi today</h2>
    <div class="player-container">
    <HlsPlayer link="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_Bukomansimbi_vod_nm/20/vod.m3u8" />
        <p>This Content is licensed and distributed exclusively by Ready Media.</p>
    </div><br>

    <a href="https://www.youtube.com/@onc_nrm">ONC youtube Channel</a><br/>
</hgroup>

    <aside>
        <h4> About Bukomansimbi</h4>
        <p>
            Bukomansimbi is a town in the Central Region of Uganda. It is the chief municipal, administrative, and commercial center of Bukomansimbi District and the site of the district headquarters.
        </p>
        <p><small>What's happening in: </small></p> <br>
        <a href="/media_WestNile">West Nile</a><br>
        <a href="/BikabyaBuganda_media">Bika bya Buganda</a><br>
    </aside>

<style>
    h2{
        text-align: center;
    }

    .player-container{
        text-align: center;
        display: flex;
        position: middle;
        flex-direction: column;
        align-items: center;
    }
</style>