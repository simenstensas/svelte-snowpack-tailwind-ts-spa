<script lang="ts">
  import Router from 'svelte-spa-router';
	import routes from './routes.js';
</script>

<div class="App">
  <Router {routes} />
</div>

<style type="text/postcss">
  :global(body) {
    @apply m-0;
    font-family: Arial, Helvetica, sans-serif;
  }
</style>