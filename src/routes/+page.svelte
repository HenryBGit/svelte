<link rel="stylesheet" href="\src\main.css">  <!-- TODO - move this away and import instead -->
<!--TODO Find the font that i used in the nav bar and change it from an image to a font-->
<script>

    let darkMode = false;
    let logo ="/images/Neoni Logo.png";
    let logoDark ="/images/Neoni Logo - Dark Mode.png";

    function myFunction() {
        document.body.classList.toggle("dark-mode");
        darkMode = !darkMode;
    }

</script>

<nav>
    <ul>
        <li><button  on:click={myFunction}><img class="button_img" src="\images\sun and moon.jpg" alt=""></button></li>
        <li><a href="/"> <img class="logo-img" alt="" src="{!darkMode ? logo : logoDark}"></a> </li>
        <li><a href="/about/Artist songs"> Songs</a></li>
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