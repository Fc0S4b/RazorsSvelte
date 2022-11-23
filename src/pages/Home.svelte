<script>
  import Hero from '../components/Hero.svelte';
  // import { Link } from 'svelte-routing';
  import { link } from 'svelte-routing';
  // featured products
  // function getProps() {
  //   return { class: 'btn btn-primary btn-hero' };
  // }
</script>

<!-- varias opciones para pasar estilos al componente, una directamente a class, otra usando getProps con Link y otra usando <a> con link  -->
<Hero>
  <!-- <Link to="/products" class='btn btn-primary btn-hero'>shop now</Link> -->
  <!-- <Link to="/products" {getProps}>shop now</Link> -->
  <a href="/products" class="btn btn-primary btn-hero " use:link>shop now</a>
</Hero>
