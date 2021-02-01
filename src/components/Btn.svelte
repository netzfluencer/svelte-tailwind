<script>
	import { createEventDispatcher } from 'svelte'

	const dispatch = createEventDispatcher()

	export let label
</script>

<button class="text-gray-100 bg-gray-800 rounded-lg" on:click={() => dispatch('click')}>{label}(Svelte)</button>
