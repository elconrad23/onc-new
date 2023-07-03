<script>
	import header from './Header.svelte';
	import Footer from './Footer.svelte';	
</script>

<div class="app">
	<header />

	<main>
		<slot />
	</main>

	<Footer />
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	/* Footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}

	Footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		Footer {
			padding: 12px 0;
		}
	} */
</style>
