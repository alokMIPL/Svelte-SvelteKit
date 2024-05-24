<script>
  import {page} from '$app/stores'
  const { productId, reviewId } = $page.params
  
</script>

<a href="/">Home</a>
<a href="/about">About</a>
<a href="/blog">Blog</a>
<a href="/docs">Docs</a>
<a href="/products">Products</a>
<a href="/profile">Profile</a>
<h1>Review {reviewId} for the Product {productId}</h1>

<a href="/products/review">Back to Review Page</a>

