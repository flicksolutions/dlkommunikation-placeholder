<script>
	import logo from '$lib/assets/logo.png?enhanced';

	console.log(logo);
</script>

<div class="center">
	<enhanced:img src={logo} alt="DL Kommunikation" />
	<div class="inner">
		<h1>DL Kommunikation: Website offline</h1>
		<p>
			Nach fast fünfzig Jahren Journalismus und zehn Jahren erfolgreicher beruflicher
			Selbständigkeit hat bei mir ein neuer Lebensabschnitt begonnen. Für ausgewählte Beratungen und
			Moderationen stehe ich weiterhin zur Verfügung.
		</p>

		<p>Daniel Lüthi</p>
		<p>Tel. <a href="tel:+41'79'753'44'47">+41 79 753 44 47</a></p>

		<p><a href="mailto:dl@dlkommunikation.ch">dl@dlkommunikation.ch</a></p>
	</div>
</div>

<style>
	:global(body) {
		background-color: #f2f2f2;
	}
	h1 {
		/* hide visually but keep accessible to screen readers;*/
		border: 0;
		clip: rect(0 0 0 0);
		height: 1px;
		margin: -1px;
		overflow: hidden;
		padding: 0;
		position: absolute;
		width: 1px;
	}

	p {
		font-family: sans-serif;
		font-size: 18px;
		max-width: 800px;
	}

	a {
		color: #af351a;
	}

	.inner {
		background-color: #fff;
		padding: 20px;
		border-radius: 10px;
		box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
	}

	/* horizontal and vertical center */
	.center {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		height: 100vh;
		gap: 2rem;
	}
</style>
