<script>
import { products } from './cart.js';
import CompCartProduct from './CompCartProduct.svelte';
</script>


<!-- ##################################################### -->
<h1>Cart</h1>
{JSON.stringify($products)}

{#each $products as product}

<CompCartProduct product={product}/>

{/each}
<!-- ##################################################### -->

<style>


</style>