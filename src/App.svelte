<script>
import LeftNav from './LeftNav.svelte'
	export let name;
</script>

<svelte:head>
	<link href="https://fonts.googleapis.com/css2?family=Montserrat&family=Questrial&display=swap" rel="stylesheet"> 
</svelte:head>
<main>
	<h1>JOSH CHUNG</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	:global(body) {
		background-color: #282B2D;
	}
	main {
		text-align: center;
		padding: 1em;
		max-width: auto;
		margin: 0 auto;
		min-height: 100%;
	}

	h1 {
		color: white;
		text-transform: uppercase;
		font-size: 4em;
		font-family: 'Montserrat', sans-serif;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>