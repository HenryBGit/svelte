<link rel="stylesheet" href="\src\main.css"> 
<script>
    import Navbar from "$lib/navbar.svelte";
	import Footer from "$lib/footer.svelte";

</script>

<main>
    <Navbar/>
    <slot/>
</main>

<h2>Neoni's Songs</h2>
<!--Could do this via an api instead of doing this over and over again-->

<a href="#" class="top">Back to Top &#8593;</a>

<main>
    <Footer />
    <slot />
</main>
<style>	
.rcorners1 {
    border-radius: 25px;
    border: 2px solid transparent;
	max-width: 350px;
    max-height: 350px;
    min-width: 350px;
    min-height: 350px;
}
.rcorners1:hover {
    opacity: 0.8;
}
@media only screen and (max-width: 600px) {
    .rcorners1{
        display: inline-block;
        max-width: 150px;
        max-height: 150px;
        min-width: 150px;
        min-height: 150px;

    }
    .line {
        grid-row: 1;
        grid-row-end: 1;
	}
}
.line {
	display: flex;
	justify-content: center;
	justify-items: center;
}
.tooltip {
  position: relative;
  display: inline-block;
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 15px;
  padding: 5px 0;

  /* Position the tooltip */
  position: absolute;
  z-index: 1;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
}
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