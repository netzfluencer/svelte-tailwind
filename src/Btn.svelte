<script>
	import { createEventDispatcher } from 'svelte'

	const dispatch = createEventDispatcher()

	export let label
</script>

<button on:click={() => dispatch('click')}>{label}(Svelte)</button>
