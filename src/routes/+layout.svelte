<script>
	import Sitename from './Sitename.svelte';
	import Header from './Header.svelte';
	import './styles.css';
</script>

<div class="app">

	<Sitename />

	<!-- <Header /> -->

	<main>
		<slot />
	</main>

	<footer>
		<p>  WELCOME TO SMRT MRKT ©  </p>
	</footer>
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

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		/* padding: 0 12px; */
		background: black;
		color: whitesmoke;
		font-size: 15px ;
		font-weight: bold;
		font-family: serif;
		border-top: 3px solid #c3d214;
	}

	/* footer a {
		font-weight: bold;
	} */

	@media (min-width: 700px) {
		footer {
			font-size: 20px;
		}

	}
</style>
