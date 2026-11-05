<svelte:options customElement="my-stepper" />

<script>
  let {max} = $props();
  let count = $state(0);
	function increment() {
    count += 1;
	}
</script>

<button onclick={increment}>
{count}
</button>

{#if count > 0 && count % max == 0}
  <h1>Wow!!</h1>
{/if}
