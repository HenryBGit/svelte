<link rel="stylesheet" type="text/css" href="/src/main.css"> 
<script>
    import Navbar from "$lib/navbar.svelte";
    import Footer from "$lib/footer.svelte";
    import FanSongs from "$lib/fanPage.svelte";
</script>
    
<main>
    <Navbar/>
    <slot/>
    <FanSongs />
    <Footer />
    <slot />
</main>