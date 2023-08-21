<script>
  import Header from './Header.svelte';
  import '../app.css';
</script>

<div class="app">
  <Header />

  <main>
    <slot />
  </main>

  <footer>
    <p> This be the footer</p>
  </footer>
</div>
  
<style>
	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
	}
</style>