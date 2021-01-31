<script>
	import { createEventDispatcher } from 'svelte'

	const dispatch = createEventDispatcher()

	export let label
</script>

<button class="bg-gray-800 rounded-lg text-gray-100" on:click={() => dispatch('click')}>{label}(Svelte)</button>
