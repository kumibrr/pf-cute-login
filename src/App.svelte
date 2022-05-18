<script>
	import Login from './components/login.svelte';
</script>

<main>
	<div>
		<Login></Login>
	</div>
</main>

<style>
	:root {
		color-scheme: light dark;
		accent-color: auto;
	}

	main {
		width: 100%;
		height: 100%;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	div {
		background-color: rgb(144, 144, 144);
		padding: 1em;
		max-width: 15rem;
		border-radius: 20px;
		box-shadow: 0px 0px 20px 20px rgba(86, 86, 86, 0.2);
	}
</style>