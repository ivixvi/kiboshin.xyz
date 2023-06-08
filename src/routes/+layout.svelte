<script lang="ts">
	import Button from '../lib/Button.svelte';
</script>

<Button>🤔</Button>

<slot />

<style>
	:global(body) {
		background-color: #f2eee2;
		color: #0084f6;
		transition: background-color 0.3s;
	}
	:global(body.dark-mode) {
		background-color: #1d3040;
		color: #bfc2c7;
	}
</style>
