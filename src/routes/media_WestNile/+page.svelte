

<script>
    import HlsPlayer from "$lib/HlsPlayer.svelte";
    import play from '/images/icons8-play-26.png';
</script>

<svelte:head>
    <title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS."/>
    <!-- Default theme. ~960B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/default.css"/>

    <!-- Optional light theme (extends default). ~400B -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@vime/core@^5/themes/light.css"/>

</svelte:head>

<form action="/">
    <div> <input type="text" class="search" placeholder="Search..">
        <button type="submit" id="search" ><i class="fa fa-search"></i></button>
    </div>
</form>

<div class="grid">
    <div>
        <h2> West Nile today</h2>
        <!--<Player/>-->
        <HlsPlayer link="https://readymedia.moderntv.cloud:8092/distribute/readymedia/ONC_WestNile_vod_px/20/vod.m3u8" />
        <p>Hajjat Hadijah Namyalo addressing the people of Arua district.</p><br/>
        <p>This Content is licensed and distributed exclusively by Ready Media.</p><br/>
        <p>Posted on: 02-07-2023</p>

        <h4> About the West Nile.</h4>
        <p>
            The sub-region is bordered by the Democratic Republic of the Congo to the south and west, by South Sudan to the north and by the Albert Nile to the east. The town of Arua, is the largest town in the sub-region. Arua lies approximately 475 kilometres (295 mi), by road, northwest of Kampala, the capital of Uganda, and the largest city in that country.    
        </p><br/>
    </div>
    <div>
        <p class="caption">What's happening in: </p> 
        <aside><nav>
            <ul>
                <li><a href="/Bukomansimbi_media">
                    <img src={play} alt="play" style="width:2em; height:2.13em; border-radius: 9%;" />
                    Bukomansimbi</a> <br/></li> 
                <li><a href="/BikabyaBuganda_media">
                    <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
                    Bika bya Buganda</a></li><br/>
                
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

        