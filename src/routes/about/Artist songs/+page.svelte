<link rel="stylesheet" href="\src\main.css"> 
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

<h2>Neoni's Songs</h2>
<div class="container">
<section class="line line-1">
<!--Need to go through each one of these and add in the links-->
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
	<a href=""></a> <img class="rcorners1"src="\images\bad intentions.jpg" alt="">
</section>
<section class="line line-9">
	<a href=""></a> <img class="rcorners1"src="\images\Big guns neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Bombs away.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Bury Me alive.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\carousel.jpg" alt="">
</section>
<section class="line line-10">
	<a href=""></a> <img class="rcorners1"src="\images\Chemcials.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Confession.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\conquer.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\dead to me.jpg" alt="">
</section>
<section class="line line-11">
	<a href=""></a> <img class="rcorners1"src="\images\deep water.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Demons.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Empire.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Feet dont fail me now.jpg" alt="">
</section>
<section class="line line-12">
	<a href=""></a> <img class="rcorners1"src="\images\gold.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Happy ever afterjpg.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\here comes trouble.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\hooligan.jpg" alt="">
</section>
<section class="line line-13">
	<a href=""></a> <img class="rcorners1"src="\images\ignite.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\im not sorry.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Long time traveller.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Messed Up Masterpiece.jpg" alt="">
</section>
<section class="line line-14">
	<a href=""></a> <img class="rcorners1"src="\images\monster.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Mutiny.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\nerver.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\oblivion.jpg" alt="">
</section>
<section class="line line-15">
	<a href=""></a> <img class="rcorners1"src="\images\Omens.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\origin neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\over my head.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\ready for war.jpg" alt="">
</section>
<section class="line line-16">
	<a href=""></a> <img class="rcorners1"src="\images\Rip neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\six feet deep.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Soilder.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\SuperNova.jpg" alt="">
</section>
<section class="line line-17">
	<a href=""></a> <img class="rcorners1"src="\images\uh oh.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\underground.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\up in flames.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Vengance.jpg" alt="">
</section>
<section class="line line-18">
	<a href=""></a> <img class="rcorners1"src="\images\Warning label.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\Wasteland.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\weirdo neoni.jpg" alt="">
	<a href=""></a> <img class="rcorners1"src="\images\wreckage neoni.jpg" alt="">
</section>
</div>

<!--On hover displays the title and artist(s) of the songs-->
<style>
	.top:hover {
		color: rgba(214, 209, 209, 0.952);
	}
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
</style>
<a href="#" class="top">Back to Top &#8593;</a>