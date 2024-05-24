<script>
  import {page} from '$app/stores';

  console.log($page.params.slug);
  const slugArr = $page.params.slug.split('/')
</script>

<a href="/">Home</a>
<a href="/about">About</a>
<a href="/blog">Blog</a>
<a href="/marketing">Marketing</a>
<a href="/products">Products</a>
<a href="/profile">Profile</a>

{#if slugArr.length === 1}
<h1>Docs home Page {slugArr[0]}</h1>
{:else if slugArr.length === 2}
<h1>Viewing docs for features {slugArr[0]} and concept {slugArr[1]}</h1>
{/if}