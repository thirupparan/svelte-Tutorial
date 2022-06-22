<script>
  import { count } from "../store/store";
  function incriment() {
    count.update((value) => {
      return value + 1;
    });
  }
</script>

<button on:click={incriment}>Incriment</button>
