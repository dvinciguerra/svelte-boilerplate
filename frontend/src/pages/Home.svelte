<script>
  import { link } from 'svelte-routing';
</script>

<main>
	<h1>Home Page!</h1>
  <p>
    <a href="/about" use:link>About Page</a>
  </p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
</style>
