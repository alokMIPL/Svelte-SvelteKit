
<script>
  import {goto} from '$app/navigation'
  const handleClick = () => {
    console.log("Placing your order");
    goto('/products')
  }
</script>

<h1>Hello Home!</h1>

<a href="/about">About</a>
<a href="/blog">Blog</a>
<a href="/docs">Docs</a>
<a href="/marketing">Marketing</a>
<a href="/products">Products</a>
<a href="/profile">Profile</a>

<button on:click={handleClick}>Place Order</button>