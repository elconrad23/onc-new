<script>
    import HlsPlayer from "$lib/HlsPlayer.svelte";
</script>

<svelte:head>
    <title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS."/>
    <!-- Default theme. ~960B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/default.css"/>

    <!-- Optional light theme (extends default). ~400B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/light.css"/>

</svelte:head>

<div class="grid">
    <section>
        <hgroup>
            <h2> Bika bya Buganda today</h2>
            <div class="player-container">
                <HlsPlayer link="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_Bika_bya_Buganda_vod_7q/20/vod.m3u8"/>
                <p>This Content is licensed and distributed exclusively by Ready Media.</p>
            </div>
            <a href="https://www.youtube.com/@onc_nrm">ONC youtube Channel</a><br/>
        </hgroup>
    <br/>
    </section>
    <aside>
        <h4> About Bika bya Buganda, home of Bika bya Buganda tournament.</h4>
        <p>
            President Yoweri Kaguta Museveni who also doubles as the ruling NRM party chairman, has contributed shs20m
            towards the Bika bya Buganda football.
        </p>
        <p><small>What's happening in: </small></p> 
        <a href="/Bukomansimbi_media">Bukomansimbi</a><br>
        <a href="/media_WestNile">West Nile</a><br>
    </aside>
</div>

<style>
    h2 {
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
