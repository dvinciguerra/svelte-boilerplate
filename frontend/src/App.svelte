<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from './pages/Home.svelte';
  import About from './pages/About.svelte';

  export let url = '';
</script>

<Router url="{url}">
  <Route path="/about" component="{About}" />
  <Route path="/"><Home /></Route>
</Router>