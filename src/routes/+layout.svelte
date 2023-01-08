<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<Header />
<slot />
<Footer />

<style>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

  .root {
    padding: 1rem;
  }
</style>
