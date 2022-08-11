<script>
	import Header from "$lib/header.svelte";
    import Footer from "$lib/footer.svelte";

    
</script>

<Header />

<main>
    <slot />
</main>


<Footer />

<style>
    :global(html) {
        font: Arial, Helvetica, sans-serif;
    }

    main {
        background-color: blanchedalmond;
    }
</style>