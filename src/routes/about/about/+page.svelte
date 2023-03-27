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
<img class="rcorners1"src="\images\Loser Neoni.jpg" alt="">
<img class="rcorners1"src="\images\Ghost Town Neoni 2.jpg" alt="">
<img class="rcorners1"src="\images\Darkside Neoni.jpg" alt="">
<img class="rcorners1"src="\images\Royalty Album Cover.jpg" alt="">



<footer>
    <ul>
        <li><a href="/"> Home</a> </li>
        <li><a href="/about/about"> Songs</a></li>
        <li><a href="/about"> About Neoni</a></li>
        <li></li>
    </ul>
</footer>