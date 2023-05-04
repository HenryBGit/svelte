<link rel="stylesheet" href="\src\main.css">  <!-- TODO - move this away and import instead -->
<!--Font used in the img: https://www.dafont.com/vogue.font?text=Neoni-->

<script>
    function myFunction() {
        document.body.classList.toggle("dark-mode");
    }
</script>
<nav>
    <ul>
        <li><button  on:click={myFunction}><img class="button_img" src="\images\sun and moon.jpg" alt=""></button></li>
        <li><a href="/"> <img class="logo-img" alt="" src="Neoni Logo.png"></a> </li>
        <li><a href="/about/artist songs"> Songs</a></li>
        <li><a href="/about"> About Neoni</a></li>
    </ul>
</nav>

<div class="main_image-container">
    <img class="background_image" src="\images\Neonoi Sisters.jpeg"  alt="">
</div>

<style>
.background_image {
	width: 100%;
	display: block;
	margin-left: auto;
	margin-right: auto;
}
</style>
   <h1>Welcome To <a href="https://www.youtube.com/watch?v=lW9ep22YmlM">Royalty</a></h1>