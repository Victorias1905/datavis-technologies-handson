<script>
  let current = "";
</script>

<!-- We will cover buttons later on! -->
<button class:selected={current === 'messi'}
class="btn btn-secondary" on:click={() => (current = "messi")}>
  Messi
</button>

<button class:selected={current === 'ronaldo'}
class="btn btn-secondary" on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class:selected={current === 'neymar'}
class="btn btn-secondary" on:click={() => (current = "neymar")}>
  Neymar
</button>

<style>
  .selected {
    background-color: lightpink;
  }
</style>



