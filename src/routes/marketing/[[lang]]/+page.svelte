<script>
  import { page } from '$app/stores'

  const greetings = {
    en:"Hello!",
    es:"Hola!",
    fr:"Bonjour!"
  };

  const {lang = 'en'} = $page.params
  const greeting = greetings[lang];
</script>


<a href="/">Home</a>
<a href="/about">About</a>
<a href="/blog">Blog</a>
<a href="/docs">Docs</a>
<a href="/products">Products</a>
<a href="/profile">Profile</a>


<h1>{greeting}</h1>