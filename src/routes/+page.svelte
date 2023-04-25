<link rel="stylesheet" href="\src\main.css"> 

<nav>
    <ul>
        <button on:click={myFunction}><img class="button_img" src="\images\sun and moon.jpg" alt=""></button>
<script>
function myFunction() {
   var element = document.body;
   element.classList.toggle("dark-mode");
}
</script>
        <li><a href="/"> <img class="logo-img" alt="" src="\images\Neoni Logo.png"></a> </li>
        <li><a href="/about/artist songs"> Songs</a></li>
        <li><a href="/about"> About Neoni</a></li>
    </ul>
</nav>

<div class="main_image-container">
    <img class="background_image" src="\images\Neonoi Sisters.jpeg"  alt="">
</div>
<style>
    
.main_image-container {
	width: 100%;
	height: 65vh;
	display: block;
	overflow: hidden;
	margin-left: auto;
	margin-right: auto;
}
.background_image {
	width: 100%;
	display: block;
	margin-left: auto;
	margin-right: auto;
}
</style>
   <h1>Welcome To <a href="https://www.youtube.com/watch?v=lW9ep22YmlM">Royalty</a></h1>