<script>
	import Title from './components/Title.svelte';
	export let name;

	let message = `Hello ${name}`
</script>

<main>
	<Title greeting {message} />
</main>

<style global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>