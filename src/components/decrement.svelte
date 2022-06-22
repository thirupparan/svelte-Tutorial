<script>
  import { count } from "../store/store";
  function decrement() {
    count.update((value) => {
      return value - 1;
    });
  }
</script>

<button on:click={decrement}>Decrement</button>
