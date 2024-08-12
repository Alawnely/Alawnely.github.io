<script>
	import '../app.css';
</script>

<main>
	<slot />
</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		width: 100%;
		min-height: 100%;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>
