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
        <li><a href="about\Artist songs"> Songs</a></li>
        <li><a href="/about"> About Neoni</a></li>
    </ul>
</nav>

<h2>About Neoni</h2>
<h3>What is Neoni?</h3>
<p></p>
<h3>What type of songs do they make?</h3>
<p></p>
<h3>How popular are they?</h3>
<p></p>

<h2>Fan Favorites</h2>
<div class="container">
    <section class="item item-1"> <a href="https://www.youtube.com/watch?v=lW9ep22YmlM"> <img src="\images\Royalty Album Cover.jpg" alt=""></a> </section>
    <section class="item item-2"> <a href="https://www.youtube.com/watch?v=UgKNP8GHnuk"> <img src="\images\Darkside Neoni.jpg" alt=""></a> </section>
    <section class="item item-3"> <a href="https://www.youtube.com/watch?v=0bTVSSiAgZs"> <img src="\images\Wonderland Neoni.jpg" alt=""> </a></section>
    <section class="item item-4"> <a href="https://www.youtube.com/watch?v=d79nXbLUUh4"> <img src="\images\Ghost Town Neoni 2.jpg" alt=""></a> </section>
    <section class="item item-5"> <a href="https://www.youtube.com/watch?v=ErJjUbAPue0"> <img src = "\images\Loser Neoni.jpg" alt=""></a>  </section>
</div>
<style>
a img:hover {
	opacity: 0.7;
}

.container {
	display: grid;
	margin: 0 auto;
    max-width: 1516px;
}

.item{
	display: flex;
	justify-content: center;
	justify-items: center;
}
.item-1 {	
	grid-column-start: 1;
	grid-column-end: 1;
	grid-column: 1;
}

.item-2 {
	grid-column-start: 2;
	grid-column-end: 1;
	grid-column: 2;
}

.item-3 {
	grid-column-start: 3;
	grid-column-end: 1;
	grid-column: 3;
}

.item-4 {
	grid-area:2 / 1 / span 1 / span 2
	/*Starting on row 2 and column 1  it will span 1 row and 1 column*/
	
}

.item-5 {
	grid-area:2 / 2 / span 1 / span 2
	/*Starting on row 2 and column 2 it will span 1 row and 2 columns*/
}
</style>
<!--Add in logos of social media here-->
<!--<footer>
    <ul>
        <li><img></li>
        <li><img></li>
        <li><img></li>
        <li><img></li>
    </ul>
</footer>-->