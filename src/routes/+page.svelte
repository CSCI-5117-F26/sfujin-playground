<script>
  import '../lib/Stepper.svelte';

  let count = $state(0);
</script>

<h1>Welcome to SvelteKit</h1>

<my-stepper
	onincrement={() => count += 1}
></my-stepper>
