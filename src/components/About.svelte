<script>
  let someText = `Fronted Developer at GAD Manta`;
  let count = 0;

  const handleClick = () => count++;
</script>

<style>
  p {
    color: var(--theme-color);
  }
</style>

<div class="About">
  <p>{someText}</p>
  <button on:click={handleClick}>Click!!! {count === 0 ? '' : count}</button>
</div>
