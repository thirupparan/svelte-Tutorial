<script>
    import { count } from "../store/store";
    function reset() {
      count.set(0)
    }
  </script>
  
  <button on:click={reset}>Reset</button>
  