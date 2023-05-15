<link rel="stylesheet" href="\src\main.css"> 
<script>
    import Navbar from "$lib/navbar.svelte";
    import Footer from "$lib/footer.svelte";
</script>

<main>
    <Navbar/>
    <slot/>
</main>



<h2>About Neoni</h2>
<h3>What are Neoni?</h3>
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
<br>
<br>
<main>
    <Footer />
    <slot />
</main>