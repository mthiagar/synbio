<script>
  import Header from "./Header.svelte";
  import "../app.css";
</script>

<div class="app">
  <Header />

    <slot />

  <footer>
    <p>Made with love by humans for the benefit of all humanity.</p>
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
