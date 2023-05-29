<link rel="stylesheet" href="\src\main.css"> 
<script>
    import Navbar from "$lib/navbar.svelte";
	import Footer from "$lib/footer.svelte";
    import Songs from "$lib/songs.svelte"

</script>

<main>
    <Navbar/>
    <slot/>
    <Songs/>
    <slot/>
</main>

<a href="#" class="top">Back to Top &#8593;</a>

<main>
    <Footer />
    <slot />
</main>

<style>	
.top {  
	position: sticky;
  	bottom: 20px;      
  	margin-right:10px; 
  	margin-top: 200vh;
  	margin-left: 170vh;
  
  	/* visual styling */
  	text-decoration: none;
  	padding: 10px;
  	font-family: sans-serif;
  	color: #fff;
  	background: #000;
  	border-radius: 100px;
}

.top:hover {
		color: rgba(214, 209, 209, 0.952);
}
</style>