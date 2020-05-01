<script>
	export let name;

	let count = false;

	function handleClick() {
		count = !count;
	}
</script>

<main>
	<h1>Hello {name}!</h1>
	<button on:click={handleClick}>
	clicks: {count}
</button>
</main>

<style>

</style>