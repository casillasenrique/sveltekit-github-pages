<script>
  import Link from '../lib/components/Link.svelte';
  import { base } from '$app/paths';

  console.log(base);
</script>

<nav>
  <ul>
    <li><Link href="/">Home</Link></li>
    <li><Link href="/resume">Resume</Link></li>
    <li><Link href="/projects">Projects</Link></li>
    <!-- <a href="{base}/">Home</a>
    <a href="{base}/resume">Resume</a>
    <a href="{base}/projects">Projects</a> -->
  </ul>
</nav>

<slot />
