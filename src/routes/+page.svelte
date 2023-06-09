<link rel="stylesheet" type="text/css" href="/src/main.css"> 
<script>
    import Navbar from "$lib/navbar.svelte";
	import MainImage from "$lib/mainImage.svelte";
    import Background from "$lib/background.svelte";
</script>

<main>
    <Background />
    <Navbar/>
    <slot/>
	<MainImage/>
	<slot/>
</main>