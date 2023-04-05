<script>
    import "$lib/styles/style.css";
    import '$lib/styles/day.css';
    import Header from "$lib/components/Header.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<Header />
<main>
  <slot />
</main>

<Footer />