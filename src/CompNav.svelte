<script>
 import { products } from './cart.js'

 let itemsInCart = 0

 $:{
     let count = 0
     for(let item of $products) {
       count += item.quantity
     }
     itemsInCart = count
 }

</script>


<!-- ##################################################### -->

<nav>
<a href="/">Home</a>
<a href="/contact-us">Contact</a>
</nav>
Items in Cart { itemsInCart}
<!-- ##################################################### -->

<style>


</style>