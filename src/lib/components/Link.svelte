<script>
  import { base } from '$app/paths';

  export let href;
  console.log(`Building link with href=${base}${href}`)
</script>

<a href="{href}" {...$$props}><slot /></a>
