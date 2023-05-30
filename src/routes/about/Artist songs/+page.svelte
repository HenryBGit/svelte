<link rel="stylesheet" href="\src\main.css"> 
<script>
    import Navbar from "$lib/navbar.svelte";
	import Footer from "$lib/footer.svelte";
    import Songs from "$lib/songs.svelte";
	import Top from "$lib/top.svelte";

</script>

<main>
    <Navbar/>
    <slot/>
    <Songs/>
	<Top/>
    <Footer />
    <slot />
</main>