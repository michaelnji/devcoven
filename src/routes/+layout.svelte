<script lang="ts">
	import '@fontsource/work-sans';
	import '@fontsource/work-sans/400.css';
	import '@fontsource/work-sans/500.css';
	import '@fontsource/work-sans/600.css';
	import '@fontsource/work-sans/700.css';
	import '@fontsource/work-sans/800.css';
	import '@fontsource/work-sans/900.css';
	import './styles.css';
</script>

<div class="app bg-base-300 !h-screen w-screen overflow-x-hidden font-body text-md">
	<header />
	<main class="pt-24 !h-full">
		<slot />
	</main>
</div>
