<script>
	import Card from '$lib/Card.svelte';
</script>

<svelte:head>
	<meta content="https://sveltekit-satori.vercel.app/og?message=Home" property="og:image" />
</svelte:head>

<div class="card">
	<Card />
</div>

<style>
	@font-face {
		font-family: 'Noto Sans';
		src: url('/src/lib/NotoSans-Regular.ttf');
	}

	.card {
		height: 630px;
		width: 1200px;
	}
</style>
