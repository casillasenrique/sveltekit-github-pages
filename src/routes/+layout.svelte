<script>
  import Link from '../lib/components/Link.svelte';
  import { base } from '$app/paths';
</script>

<nav>
  <ul>
    <!-- <li><Link href="/">Home</Link></li>
    <li><Link href="/resume">Resume</Link></li>
    <li><Link href="/projects">Projects</Link></li> -->
    <a href="{base}/">Home</a>
  </ul>
</nav>

<slot />
