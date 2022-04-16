<script lang="ts">
  export let onClick: () => void;
  export let classNames = '';
</script>

<button class={`${classNames} mt-10 border border-gray-800 rounded-full p-2 shadow shadow-gray-800 bg-white text-gray-800`} on:click={onClick}><slot /></button>