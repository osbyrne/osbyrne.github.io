<script lang="ts">
  import osbyrneLogo from './assets/osbyrne.png'
  import Counter from './lib/Counter.svelte'
</script>

<main>
  <div>
    <a href="https://bento.me/osbyrne" target="_blank" rel="noreferrer">
      <img src={osbyrneLogo} class="logo osbyrne" alt="Osbyrne Logo" />
    </a>
  </div>
  <h1>Osbyrne</h1>

  <div class="card">
    <Counter />
  </div>
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter 300ms;
  }
  .logo.osbyrne:hover {
    filter: drop-shadow(0 0 2em #ff00f7aa);
  }
</style>
