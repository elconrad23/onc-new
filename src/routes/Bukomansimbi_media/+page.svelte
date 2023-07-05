
<script>
    import HlsPlayer from "$lib/HlsPlayer.svelte";
    import play from '/images/icons8-play-26.png';
    import bika from '/images/bika.png';
    import west from '/images/west.png';
</script>

<svelte:head>
	<title>ONC • Uganda</title>
    <meta name="description" content="A classic government company. Built with CSS." />
    <!-- Default theme. ~960B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/default.css"/>

    <!-- Optional light theme (extends default). ~400B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/light.css" />

</svelte:head>

<form action="/">
    <div> 
        <input type="text" class="search" placeholder="Search..">
    </div>
</form>

<div class="grid">
    <div >
        <h2> Bukoma Nsimbi today</h2>
        <span>
        <HlsPlayer link="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_Bukomansimbi_vod_nm/20/vod.m3u8" /><br>
        </span>
        <p>Womens' day in Bukomansimbi district.</p>
        <p>This Content is licensed and distributed exclusively by Ready Media Africa.</p>
        <p>Posted on: 02-07-2023</p>
        <p>
            <a href="/future_media">Set alert for future event</a>
        </p>
        <h4> About Bukomansimbi</h4>
        <p>
            Bukomansimbi is a town in the Central Region of Uganda. It is the chief municipal, administrative, and commercial center of Bukomansimbi District and the site of the district headquarters.
        </p>
    </div>
    <div>
        <p class="caption">What's happening in: </p> 
           <aside><nav> <ul>
                <li><ul>
                    <li>
                        <a href="/BikabyaBuganda_media">
                        <img src="{bika}" alt="thumbnail" style="width:12em; height:6.13em;"/>
                        </a>
                    </li>
                    <li><a href="/BikabyaBuganda_media">
                    <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
                    Bika bya Buganda</a></li></ul>
                    </li><br/>
                <ul>
                    <li>
                        <a href="/media_WestNile">
                        <img src={west} alt="thumbnail" style="width:12em; height:6.13em;"/>
                        </a>
                    </li><li> <a href="/media_WestNile">
                    <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
                    West Nile</a><br/></li></ul><br/>
                <br/>
                
    </ul></nav></aside></div>
</div>

<style>
    h2 {
        text-align: center;
    }

    .search{
        float: right;
        padding: 6px;
        width:19em;
        border: 1px aquamarine;
        border-radius: 9%;
        margin-top: 8px;
        margin-right: 16px;
        font-size: 19px;
    }



    @media screen and (max-width: 600px) {
        input[type=text] {
            float: none;
            display: block;
            text-align: left;
            width: 100%;
            margin: 0;
            padding: 14px;
            border: 1px solid #ccc;
        }
    }
</style>
