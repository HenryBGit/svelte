<link rel="stylesheet" href="\src\main.css">  <!-- TODO - move this away and import instead -->
<script>
    import Navbar from "$lib/navbar.svelte";
	import MainImage from "$lib/mainImage.svelte";
</script>

<main>
    <Navbar/>
    <slot/>
	<MainImage/>
	<slot/>
</main>