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


<h2>Neoni's Songs</h2>
<div class="container">
<section class="line line-1">
<!--Need to go through each one of these and add in more songs and all the links-->
	<a href=""></a> <img class="rcorners1"src="\images\Darkside Neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Wonderland Neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Ghost Town Neoni 2.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Loser Neoni.jpg" alt="">
</section>
<section class="line line-2">
	<a href=""></a> <img class="rcorners1"src="\images\Army Neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\fangs neoni 3.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\parnoia Neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Horror Movies.jpg" alt="">
</section>
<section class="line line-3">
	<a href=""></a> <img class="rcorners1"src="\images\Donwfall.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Pinky Promise.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Doomsday.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\carry on wayward song.jpg" alt="">
</section>
<section class="line line-4">
	<a href=""></a> <img class="rcorners1"src="\images\giants.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Boo hoo.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Haunted house.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Outlaw.jpg" alt="">
</section>
<section class="line line-5">
	<a href=""></a> <img class="rcorners1"src="\images\machine neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\where we rise.jpg" alt="">
	<a href=""></a>	 <img class="rcorners1"src="\images\never say die.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\mayhem neoni.jpg" alt="">
</section>
<section class="line line-6">
	<a href=""></a> <img class="rcorners1"src="\images\levitate neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\sanctuary.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\champion.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Fallout neoni.jpg" alt="">
</section>
<section class="line line-7">
	<a href=""></a> <img class="rcorners1"src="\images\Notorious.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\nightmare.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\throne.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\revolution.jpg" alt="">
</section>
<section class="line line-8">
	<a href=""></a> <img class="rcorners1"src="\images\back from the dead.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\bloodstream.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\end of the world.jpg" alt="">
</section>
<section class="line line-9">


</section>

</div>
<!--On hover displays the title and artist(s) of the songs-->
<style>
.top {
	--offset: 50vh; 
	position: sticky;
	bottom: 20px;      
	right:10px; 
	place-self: end;
	margin-left: calc(100vh + 75vh);/*sets it to the right*/
	margin-top: calc(100vh + var(--offset));/*Checking if the view height of the page is 100 and if the offset is 50px
	if it is then it wont display the button if it is not then it will show the button*/
	/* visual styling */
	text-decoration: none;
	padding: 10px;
	font-family: sans-serif;
	color: #ececec;
	background-color: #000;
	border-radius: 100px;
	white-space: nowrap;
	scroll-behavior: smooth;
  }
/*End Of Back to top button*/

.rcorners1 {
	display: flex;
    min-height: 300px;
	max-height: 300px;
	max-width: 300px;
	min-width: 300px;
    border-radius: 25px;
    border: 5px solid transparent;
	transition: all 0.5s ease-out;
  }
  .rcorners1:hover {
	transform: scale(1.5);
  }

.line {
	display: flex;
	justify-content: center;
	justify-items: center;
}
.line-1 {
	grid-row-start: 1;
	grid-row-end: 1;
	grid-row: 1;
}
.line-2 {
	grid-row-start: 2;
	grid-row-end: 2;
	grid-row: 2;
}
.line-3 {
	grid-row-start: 3;
	grid-row-end: 3;
	grid-row: 3;
}
.line-4 {
	grid-row-start: 4;
	grid-row-end: 4;
	grid-row: 4;
}
.line-5 {
	grid-row-start: 5;
	grid-row-end: 5;
	grid-row: 5;
}
.line-6 {
	grid-row-start: 6;
	grid-row-end: 6;
	grid-row: 6;
}
.line-7 {
	grid-row-start: 7;
	grid-row-end: 7;
	grid-row: 7;
}
.line-8 {
	grid-row-start: 8;
	grid-row-end: 8;
	grid-row: 8;
}
.line-9 {
	grid-row-start: 9;
	grid-row-end: 9;
	grid-row: 9;
}
</style>
<a href="#" class="top">Back to Top &#8593;</a>