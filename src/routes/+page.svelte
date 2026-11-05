<script>
  import '#lib/Stepper.svelte';

  let count = $state(0);
</script>

<h1>Welcome to SvelteKit</h1>

<my-stepper max=5></my-stepper>
<my-stepper max=3></my-stepper>
