<script>
  import { count } from "../store/store";
  let counter;
  count.subscribe((value) => {
    counter = value;
  });
</script>

<h2>Current count is {counter}</h2>
