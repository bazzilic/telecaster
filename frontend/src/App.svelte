// src/App.svelte
<script lang="ts">
  let message: string = 'Hello, AWS + Svelte World!';
</script>

<main>
  <h1>{message}</h1>
  <p>This is a simple Svelte application deployed on AWS!</p>
</main>

<style>
  main {
    text-align: center;
    padding: 20px;
    max-width: 600px;
    margin: 0 auto;
    font-family: Arial, sans-serif;
  }

  h1 {
    color: #333;
    font-size: 2.5rem;
  }
</style>