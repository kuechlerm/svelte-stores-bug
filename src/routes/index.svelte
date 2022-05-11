<script>
  import { asyncReadable } from '@square/svelte-store';
  const ar = asyncReadable(null, () => Promise.resolve());
</script>

<h1>Welcome to SvelteKit</h1>
<p>
  Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
</p>
