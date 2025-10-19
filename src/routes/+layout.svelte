<script>
	import { injectAnalytics } from '@vercel/analytics/sveltekit';
	import '../app.css';
</script>

<div class="app">
	<main>
		<slot />
	</main>

	<style lang="postcss">
	</style>
</div>
