<script lang="ts">
  import svelteLogo from './assets/svelte.svg'
</script>

<main>
  <img src={svelteLogo} class="logo" alt="Svelte Logo" />
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
</style>
