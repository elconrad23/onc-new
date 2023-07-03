<svelte:head>
	<title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS." />
    <link rel="icon" href={tabicon} type="image/png"/>
    <link rel="canonical" href="https://picocss.com/examples/company/" />
    <!-- Pico.css -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css" />
		
</svelte:head>

<script>
    import tabicon from '/images/icons8-uganda-48.png';	
    import play from '/images/icons8-play-26.png';
    import HlsPlayer from "$lib/HlsPlayer.svelte";
</script>

<form action="/">
    <div> <input type="text" class="search" placeholder="Search..">
        <button type="submit" id="search" ><i class="fa fa-search"></i></button>
    </div>
</form>

<div class="grid">
    <div>
    <h2> Bika bya Buganda today</h2><br/> 
        <HlsPlayer link="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_Bika_bya_Buganda_vod_7q/20/vod.m3u8"/>
        <br/>
        <p>This Content is licensed and distributed exclusively by Ready Media.</p><br/>
        <p>The ONC Team in Bika bya Buganda for the Endorsement of @KagutaMuseveni come 2026 .🔥🔥. </p>
        <br/>
    </div>
<div>
    <p class="caption">All media</p>
    <aside><nav>
        <ul>
            <li><a href="/Bukomansimbi_media">
                <img src={play} alt="play" style="width:2em; height:2.13em; border-radius: 9%;" />
                Bukomansimbi</a> <br/></li> 
            <li><a href="/BikabyaBuganda_media">
                <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
                Bika bya Buganda</a></li><br/>
            <li> <a href="/media_WestNile">
                <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
                West Nile</a><br/></li><br/>
            <a href="https://www.youtube.com/@onc_nrm">ONC youtube Channel</a>
            <br/>
</ul></nav></aside></div></div>


<style>
    .caption{
        text-align: center;
        position: bottom;
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