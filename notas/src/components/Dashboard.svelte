<script>
  export let notes;
  import Note from "./Note.svelte";
</script>

<div class="Dashboard">
  <div class="notes-container">
    {#each notes as {title, color, text}}
      <Note {title} {color} {text}/>
    {/each}
  </div>
</div>

<style>
</style>
