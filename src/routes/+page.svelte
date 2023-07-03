
<script src="js/minimal-theme-switcher.js">
	import chiefmuzu from '/images/chiefmuzu.jpeg';
	import hosting from '/images/hosting.jpeg';
	import cmnbs from '/images/cmnbs.jpeg';	
	import cm from '/images/cm.jpg';	
	import sojaz from '/images/sojaz.jpg';	
	import cmonroad from '/images/cmonroad.jpeg';	
	import namclap from '/images/namclap.jpg';		
</script>

<svelte:head>
	<title>ONC • Ug</title>
    <meta name="description" content="A classic government company. Built with CSS." />

	<!--Just for referrence purpose -->
    <link rel="canonical" href="https://picocss.com/examples/company/" />

</svelte:head>

<main class="container" style="padding-bottom:0px; margin-top:1.3em; margin-bottom:0px;">
	<div class="grid" style="padding-bottom:0px; margin-bottom:0px;">
		<hgroup>
			<h1 style="font-size: larger;"><strong>Our motivation </strong></h1>
			<p><small>The mantle of securing the future of Uganda is so great a task for one to play bets on. It is not a gamble and should be entrusted only with an able leader.</small></p>
			<img src={namclap} alt="H.E omalako" />
		  	
			<h3 style="font-size: larger;"><strong>Our Jajja's story</strong></h3>
		  	<img src={chiefmuzu} alt="Hajjat Hadijah and H.E together" />
		<p><small>
		  <strong>The National chairman, H.E Yoweri Kaguta Museveni</strong> was born on 15th September 1944 in Ntungamo to Amos Kaguta and Esteri Kokundeka. The name Museveni means “Son of a man of the Seventh” in honour of the Seventh Battalion of the King´s African Rifles where his father Amos Kaguta served during the World War II. In his early years Yoweri helped his father as a cattle herdsman. His diligence and an extraordinary memory earned him a place at Kyamate Elementary School, Mbarara High School, Ntare School and later University at Dar es Salaam in Tanzania, where he studied economics and political science. While at the University, he formed and got involved in various student´s revolutionary fronts and political groups that formed his views. And it was during his studies at Kyamate School where he met Janet Kataaha, who became his life love, a wife and plays an important role in his political and personal life.
		</small></p>
		
		<h3><strong>Health Of the Nation</strong></h3>
		<img src={hosting} alt="health"/>
		<p><small><strong>Progress: </strong>In response to the COVID-19 pandemic, Government committed Ush31.032 billion to support scientists in the local development of COVID-19 vaccines, drugs and diagnostics.</small></p>
		</hgroup>  

	  <aside style="margin-bottom:0em;">
		<h3>Updates: </h3>
		<a href="/" aria-label="Example" onclick="event.preventDefault()"><img src={cmnbs} alt="Crowd"/></a>
		<figure>
			<figcaption>
			<a href="/" onclick="event.preventDefault()">
				Uzeiye Hadijah @ChiefMuzzukulu
				</a><br />
			</figcaption>
		  <figure/>
		<p>
		  <small> 
			UPDATE: The Head of the Office of the National Chairman @NRMOnline, SPA Hajjat Hadijah Namyalo together with @HonKyeyune brought business in Masaka City to a standstill as they led a procession of Masaka City residents to Nyendo Market.
			#NBSUpdates May 22 
			@nbstv and @ChiefMuzzukulu
			The program is part of President @KagutaMuseveni’s wider wealth creation initiative.</small>
		</p>
		<a href="/" aria-label="Example" onclick="event.preventDefault()">
		  <img src={cmonroad} alt="youth"/></a>
		<figure>
		  <figcaption>
		<a href="/" onclick="event.preventDefault()">
		  Uzeiye Hadijah @ChiefMuzzukulu
		  </a><br />
		</figcaption>
		<figure/>
	  <p>
		<small> 
		  UPDATE: The Head of the Office of the National Chairman @NRMOnline, SPA Hajjat Hadijah Namyalo together with @HonKyeyune brought business in Masaka City to a standstill as they led of Masaka City to the Market.
		  #NBSUpdates May 22 
		  @nbstv and @ChiefMuzzukulu
		  The program is part of President @KagutaMuseveni’s wider wealth creation initiative. </small>
	  </p>
		<a href="/" aria-label="Example" onclick="event.preventDefault()"
		  ><img src= {sojaz} alt="Group muchakamuchaka"
		/></a>
		<p>
		  <a href="/" onclick="event.preventDefault()">@NRMOnline and @HonKyeyune</a><br />
		  <small>This is ahead of the #PresidentialTour of Greater Masaka starting on 23rd May 2023. They participated in a cleaning exercise of the market.</small>
		</p>
		<a href="/" aria-label="Example" onclick="event.preventDefault()"
		  ><img src={cm} alt="Architecture"
		/></a>
		<p>
		  <a href="/" onclick="event.preventDefault()">ChiefMuzzukulu speaks to youth in the Nation</a><br />
		  <small
			>I urge all bazzukulu across the country to embrace @GovUganda programs like PDM and Emyooga which have been designed under the guidance of our able leader H.E President 
			@KagutaMuseveni. We must make that shift into the money economy to end poverty.</small
		  >
		</p>
	  </aside>
	</div>
  </main>
  <!-- ./ Main -->

<style>
	.container{
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	hgroup img{
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	h1, h3 {
		text-align: center;
		color: #26619C;
		font-weight: bold;
		width: 100%;
	}

	
</style>
