<script>
  import { base } from '$app/paths';

  export let href;

  console.log(base, href);
</script>

<a href="{base}{href}" {...$$props}><slot /></a>
