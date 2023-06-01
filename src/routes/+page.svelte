<script>
	let i = 0;
</script>

<main class="h-screen flex flex-col gap-4 items-center bg-blue-400 justify-center">
	<h1 class="text-2xl font-semibold">SvelteKit + Electron + Tailwind CSS</h1>
	<button
		class="bg-white py-2 px-4 rounded-lg active:scale-95 transition:all"
		on:click={() => i++}
	>
		Click me: <b>{i}</b>
	</button>
</main>
