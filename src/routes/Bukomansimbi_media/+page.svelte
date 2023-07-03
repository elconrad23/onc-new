
<script>
    import HlsPlayer from "$lib/HlsPlayer.svelte";
    import play from '/images/icons8-play-26.png';
</script>

<svelte:head>
	<title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS." />
    <!-- Default theme. ~960B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/default.css"/>

    <!-- Optional light theme (extends default). ~400B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/light.css" />

</svelte:head>

<form action="/">
    <div> <input type="text" class="search" placeholder="Search..">
        <button type="submit" id="search" ><i class="fa fa-search"></i></button>
    </div>
</form>

<div class="grid">
    <div><h2> Bukoma Nsimbi today</h2>
    <HlsPlayer link="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_Bukomansimbi_vod_nm/20/vod.m3u8" />
    <p>Womens' day in Bukomansimbi district.</p>
    <p>This Content is licensed and distributed exclusively by Ready Media.</p>
    <p>Posted on: 02-07-2023</p>
        <br>
        <h4> About Bukomansimbi</h4>
        <p>
            Bukomansimbi is a town in the Central Region of Uganda. It is the chief municipal, administrative, and commercial center of Bukomansimbi District and the site of the district headquarters.
        </p><br/>
    </div>
    <div>
        <p class="caption">What's happening in: </p> 
        <aside><nav>
            <ul>
                 
                <li><a href="/BikabyaBuganda_media">
                    <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
                    Bika bya Buganda</a></li><br/>
                <li> <a href="/media_WestNile">
                    <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
                    West Nile</a><br/></li><br/>
                <a href="https://www.youtube.com/@onc_nrm">ONC youtube Channel</a>
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
        border: none;
        margin-top: 8px;
        margin-right: 16px;
        font-size: 17px;
    }

    #search {
        width: 3.3em;
        border-radius: 20%;
        color: #F4C430;
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
