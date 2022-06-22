<script>
  import Decrement from "./components/decrement.svelte";
  import Display from "./components/display.svelte";
  import Incriment from "./components/incriment.svelte";
  import Reset from "./components/reset.svelte";
</script>

<main>
  <Display />
  <Incriment />
  <Decrement />
  <Reset />
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }
  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
