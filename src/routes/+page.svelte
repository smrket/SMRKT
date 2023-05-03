<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';

	
</script>

<svelte:head>
	<title>SMRT MRKT Simple Life</title>
	<meta name="description" content="SMRKT APP" />
</svelte:head>

<section>
	

	<h1 style="font-family: 'Instrument Serif', serif; background:black;border-radius:20px;">#Simple Life#</h1>

	
	
	<div class="about">
		<h2>About Us</h2>
		<p>Smrt Mrkt is an emerging company.
		<br />Specialized in the field of media services and modern technology.</p>
		
		<hr />
		
		<br />
		<h2>Our Services</h2>
		<ul>
			<li>Payment of bills.</li>
			<li>Money transfer.</li>
			<li>Phone refill.</li>
		</ul>
		<hr />

	</div>

	
	
	
	<!-- <div class="pub">
		<Ad />
	</div> -->

	<!-- <h1>
		<span class="welcome">
			<picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture>
		</span>

		to your new<br />SvelteKit app
	</h1>

	<h2>
		try editing <strong>src/routes/+page.svelte</strong>
	</h2>

	<Counter /> -->
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		/* justify-content: center; */
		align-items: center;
		flex: 0.6;
		
		
	}

	h1 {
		width: 100%;
	}

	hr {
		width: 100%;
		
	}

	/* .welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	} */
</style>
