<script>
  import Page from "../lib/page.svelte";
  import Sidebar from "../lib/sidebar.svelte";
</script>

<div class="app__inner">
  <Sidebar />
  <Page />
</div>

<style>
  :global(body) {
    background-color: whitesmoke;
    font-family: "Poppins", sans-serif;
    line-height: 24px;
    font-weight: 400;
  }

  :global(*) {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }

  :global(.app) {
    padding: 2rem;
  }

  .app__inner {
    padding: 15px 30px;
  }
</style>
