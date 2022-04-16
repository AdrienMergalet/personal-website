<script lang="ts">
  import Button from '../../components/Button/Button.svelte';

  const onClick = () => console.log('Clicked');
</script>

<section class='bg-blue-400' id='home'>
  <div class='container pt-24'>
    <div class='text-white text-4xl font-thin'>
      Hi, I'm <br />
      <span class='font-bold'>Adrien Mergalet</span><br />
      Expert frontend developer
    </div>
    <Button onClick={onClick} classNames='mt-10'>Let us talk</Button>
  </div>
</section>