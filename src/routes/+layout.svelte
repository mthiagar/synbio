<script>
  import Header from "./Header.svelte";
  import "../app.css";
</script>

<div class="app">
  <Header />

    <slot />

  <footer>
    <p>&#x1F30D &#x1F30E &#x1F30F | Made with &#x1F49A.</p>
  </footer>
</div>

<style>
  .app {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }
  footer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 12px;
  }
  @media (min-width: 480px) {
    footer {
      padding: 12px 0;
    }
  }
</style>
