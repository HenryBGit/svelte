<link rel="stylesheet" href="\src\main.css">  <!-- TODO - move this away and import instead -->
<!--Font used in the img: https://www.dafont.com/vogue.font?text=Neoni-->

<script>
    import Navbar from "$lib/navbar.svelte";
</script>

<main>
    <Navbar/>
    <slot/>
</main>


<div class="main-image-container">
    <img class="background_image" src="\images\Neonoi Sisters.jpeg"  alt="">
</div>

<style>
.main-image-container {
	width: 100%;
	height: 60vh;
	display: block;
	overflow: hidden;
	}
.background_image {
	width: 100%;
	display: block;
	margin-left: auto;
	margin-right: auto;
}
</style>
   <h1>Welcome To <a href="https://www.youtube.com/watch?v=lW9ep22YmlM">Royalty</a></h1>
