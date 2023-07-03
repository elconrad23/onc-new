<svelte:head>
	<title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS." />
    <link rel="icon" href={tabicon} type="image/png"/>
    <link rel="canonical" href="https://picocss.com/examples/company/" />

</svelte:head>

<script>
    import tabicon from '/images/icons8-uganda-48.png';	
    import play from '/images/icons8-play-26.png';
</script>

<p class="caption">Coverage for regions with current feed</p>
<ul>
   <a href="/Bukomansimbi_media">
    <img src={play} alt="play" style="width:2em; height:2.13em; border-radius: 9%;" />
    Bukomansimbi</a> <br/>
    <a href="/BikabyaBuganda_media">
    <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
    Bika bya Buganda</a><br/>
    <a href="/media_WestNile">
    <img src={play} alt="play" style="width: 2em; height:2.13em; border-radius: 9%;" />
    West Nile</a><br/><br/>
    <a href="https://www.youtube.com/@onc_nrm">ONC youtube Channel</a>
    <br/>
 
</ul>

<style>
    .caption{
        text-align: center;
        position: bottom;
    }
</style>