<link rel="stylesheet" href="\src\main.css"> 
<script>
    import Navbar from "$lib/navbar.svelte";
    import Footer from "$lib/footer.svelte";
    import FanSongs from "$lib/fanSongs.svelte";
</script>

<main>
    <Navbar/>
    <slot/>
</main>

<h2>About Neoni</h2>
<h3>What are Neoni?</h3>
<p></p>
<h3>What type of songs do they make?</h3>
<p></p>
<h3>How popular are they?</h3>
<p></p>

<main>
    <FanSongs />
    <slot />
    <Footer />
    <slot />
</main>