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
        <li><a href="/"> Home</a> </li>
        <li><a href="/about/about"> Songs</a></li>
        <li><a href="/about"> About Neoni</a></li>

    </ul>
</nav>


<h2>Neoni Songs</h2>
<div class=".container">
<section class="line-1">
	<!--Need to go through each one of these and add in more songs and all the links-->
<img class="rcorners1"src="\images\Darkside Neoni.jpg" alt="">
<img class="rcorners1"src="\images\Wonderland Neoni.jpg" alt="">
<img class="rcorners1"src="\images\Ghost Town Neoni 2.jpg" alt="">
</section>
<section class="line-2">
<img class="rcorners1"src="\images\Loser Neoni.jpg" alt="">
<img class="rcorners1"src="\images\Army Neoni.jpg" alt="">
<img class="rcorners1"src="\images\fangs neoni.jpg" alt="">
</section>
<section class="line-3">
<img class="rcorners1"src="\images\parnoia Neoni.jpg" alt="">
<img class="rcorners1"src="\images\Horror Movies.jpg" alt="">
<img class="rcorners1"src="\images\Donwfall.jpg" alt="">
</section>
<section class="line-4">
<img class="rcorners1"src="\images\Pinky Promise.jpg" alt="">
<img class="rcorners1"src="\images\Doomsday.jpg" alt="">
<img class="rcorners1"src="\images\carry on wayward song.jpg" alt="">
</section>
<section class="line-5">
<img class="rcorners1"src="\images\giants.jpg" alt="">
<img class="rcorners1"src="\images\Boo hoo.jpg" alt="">
<img class="rcorners1"src="\images\Haunted house.jpg" alt="">
</section>
<section class="line-6">
<img class="rcorners1"src="\images\Outlaw.jpg" alt="">
<img class="rcorners1"src="\images\machine neoni.jpg" alt="">
<img class="rcorners1"src="\images\where we rise.jpg" alt="">
</section>
<section class="line-7">
<img class="rcorners1"src="\images\never say die.jpg" alt="">
<img class="rcorners1"src="\images\mayhem neoni.jpg" alt="">
<img class="rcorners1"src="\images\levitate neoni.jpg" alt="">
</section>
<section class="line-8">
<img class="rcorners1"src="\images\sanctuary.jpg" alt="">
<img class="rcorners1"src="\images\champion.jpg" alt="">
<img class="rcorners1"src="\images\Fallout neoni.jpg" alt="">
</section>
<section class="line-9">
<img class="rcorners1"src="\images\Notorious.jpg" alt="">
<img class="rcorners1"src="\images\nightmare.jpg" alt="">
<img class="rcorners1"src="\images\throne.jpg" alt="">
</section>
<section class="line-10">
<img class="rcorners1"src="\images\revolution.jpg" alt="">
<img class="rcorners1"src="\images\back from the dead.jpg" alt="">
<img class="rcorners1"src="\images\bloodstream.jpg" alt="">
</section>
<section class="line-11">
<img class="rcorners1"src="\images\end of the world.jpg" alt="">
</section>
</div>

<style>
section a {
    font-size: 3.5vh; 
    text-decoration: underline;
    color: black;
}
section a:hover {
    text-decoration: none;
}
.dark-mode section a {
	display: block;
    color: #ececec;
}

.line-1 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 1;
	grid-row-end: 1;
	grid-row: 1;
}
.line-2 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 2;
	grid-row-end: 2;
	grid-row: 2;
}
.line-3 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 3;
	grid-row-end: 3;
	grid-row: 3;
}
.line-4 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 4;
	grid-row-end: 4;
	grid-row: 4;
}
.line-5 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 5;
	grid-row-end: 5;
	grid-row: 5;
}
.line-6 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 6;
	grid-row-end: 6;
	grid-row: 6;
}
.line-7 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 7;
	grid-row-end: 7;
	grid-row: 7;
}
.line-8 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 8;
	grid-row-end: 8;
	grid-row: 8;
}
.line-9 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 9;
	grid-row-end: 9;
	grid-row: 9;
}
.line-10 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 10;
	grid-row-end: 10;
	grid-row: 10;
}
.line-11 {
	display: flex;
	justify-content: center;
	justify-items: center;
	grid-row-start: 11;
	grid-row-end: 11;
	grid-row: 11;
}
</style>

<footer>
    <ul>
        <li><a href="/"> Home</a> </li>
        <li><a href="/about/about"> Songs</a></li>
        <li><a href="/about"> About Neoni</a></li>
        <li></li>
    </ul>
</footer>