<script>
  import { base } from '$app/paths';

  export let href;
</script>

<a href="{base}{href}" {...$$props}><slot /></a>
