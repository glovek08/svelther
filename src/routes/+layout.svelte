<script>
  import '../app.css';
  import Footer from '$lib/components/Footer.svelte';
  import Header from '$lib/components/Navbar.svelte';
</script>

<Header />

<main>
  <slot /> <!-- This is where +page.svelte content goes -->
</main>

<Footer />