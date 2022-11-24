<script>
  import { onMount, onDestroy } from 'svelte';
  import products from '../../stores/defaultProducts';
  // let localProducts = $products;
  // console.log(products);
  // console.log($products);
</script>

<h1>hello from products component</h1>
{#each $products as product}
  <h2>{product.title}</h2>
{/each}
