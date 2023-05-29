<h2>Fan Favorites</h2>
<div class="container">
    <section class="item item-1"> <a href="https://www.youtube.com/watch?v=lW9ep22YmlM"> <img src="\images\Royalty Album Cover.jpg" alt=""></a> </section>
    <section class="item item-2"> <a href="https://www.youtube.com/watch?v=UgKNP8GHnuk"> <img src="\images\Darkside Neoni.jpg" alt=""></a> </section>
    <section class="item item-3"> <a href="https://www.youtube.com/watch?v=0bTVSSiAgZs"> <img src="\images\Wonderland Neoni.jpg" alt=""> </a></section>
    <section class="item item-4"> <a href="https://www.youtube.com/watch?v=d79nXbLUUh4"> <img src="\images\Ghost Town Neoni 2.jpg" alt=""></a> </section>
    <section class="item item-5"> <a href="https://www.youtube.com/watch?v=ErJjUbAPue0"> <img src = "\images\Loser Neoni.jpg" alt=""></a>  </section>
</div>
<style>
    .container {
        display: grid;
        grid-template-columns: repeat(6, 1fr);
        overflow: hidden;
        width: 80%;
        margin:auto;
    }
    .item {
        overflow: hidden;
        display: flex;
        justify-content: center;
        width: 200%;
    }
    .item:hover {
        opacity: 0.7;
    }
    .item-1{ grid-column:1; }
    .item-2{ grid-column:3; }
    .item-3{ grid-column:5; }
    .item-4{ grid-column:2; }
    .item-5{ grid-column:4; }    
   
   img {
    width: 100%;
   }
</style> 