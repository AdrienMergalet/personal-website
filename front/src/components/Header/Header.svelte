<script lang="ts">
  import NavLink from './NavLink.svelte';
</script>

<header class='bg-blue-400'>
  <div class='container py-2 flex items-center justify-between'>
    <div class='text-white'>Adrien Mergalet</div>
    <nav>
      <ul class='flex items-center'>
        <NavLink to={'#home'}>Home</NavLink>
        <NavLink to={'#services'}>Services</NavLink>
        <NavLink to={'#contact'}>Contact</NavLink>
        <NavLink to={'/blog'} newTab>Blog</NavLink>
      </ul>
    </nav>
  </div>
</header>