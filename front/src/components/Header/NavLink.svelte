<script lang="ts">
  export let to = '#';
  export let newTab = false;
</script>

<li class='first-of-type:ml-0 ml-5'>
  <a class='font-semibold text-white hover:text-gray-800 uppercase' href={to} target={newTab ? '_blank' : '_self'}><slot /></a>
</li>