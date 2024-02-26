<script>
  import { page } from '$app/stores';
  let pages = [
    { url: './', title: 'Home' },
    { url: './projects', title: 'Projects' },
    { url: './cv', title: 'CV' },
    { url: './contact', title: 'Contact' },
    { url: 'https://github.com/leaverou', title: 'GitHub' },
  ];
</script>

<nav>
  {#each pages as p}
    <a href={p.url} class:current={'.' + $page.route.id === p.url}>{p.title}</a>
  {/each}
</nav>
<!-- <nav>
    {#each pages as p }
      { p.url } { p.title }
    {/each}
  </nav> -->
