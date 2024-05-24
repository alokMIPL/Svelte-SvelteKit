<script>
 export let productId = 200;
</script>

<a href="/">Home</a>
<a href="/about">About</a>
<a href="/blog">Blog</a>
<a href="/docs">Docs</a>
<a href="/products">Products</a>
<a href="/profile">Profile</a>

<h1>Product List</h1>
<h2><a href="products/1">Product 1</a></h2>
<h2><a href="products/2">Product 2</a></h2>
<h2><a href="products/3">Product 3</a></h2>
<h2><a href="products/4">Product 4</a></h2>
<h2><a href="products/5">Product 5</a></h2>
<h2><a href="products/6">Product 6</a></h2>
<h2><a href={`/products/${productId}`}>Product 200</a></h2>

<a href="/products/review">Review Specific Products</a>