<script>
  let count = 0;
  $: total = count;

  function handleClick() {
    count++;
  }
</script>

<div class="Button">
  <button on:click={handleClick}>Click me</button>
  <div>You click {total} times</div>
</div>

<style>
</style>
