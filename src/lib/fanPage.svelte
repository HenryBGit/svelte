<h2>About Neoni</h2>
<h3>Who are Neoni?</h3>
<p>Neoni was formed by the Sisters Caitlin Powell and Sidney Powell and still consits of them today.</p>
<h3>What Genre of songs do they make?</h3>
<p>The Genre of thier music combines modern alternative pop and electronic music.</p>
<h3>How popular are they?</h3>
<p>Neoni is a popular modern alternative pop and electronic duo.<br> They average about 5.4 million monthly listners on spotify as of the 6th of June 2023.</p>


<h2>Fan Favorites</h2>
<div class="container">
    <div class="upside-triangle-mask"> 
        <a href="https://www.youtube.com/watch?v=lW9ep22YmlM"> <img src="\images\Royalty Album Cover.jpg" alt=""></a> 
    </div>
    <div class="triangle-mask"> 
        <a href="https://www.youtube.com/watch?v=UgKNP8GHnuk"> <img src="\images\Darkside Neoni.jpg" alt=""></a>
    </div> 
    <div class="upside-triangle-mask">
        <a href="https://www.youtube.com/watch?v=0bTVSSiAgZs"> <img src="\images\Wonderland Neoni.jpg" alt=""> </a>
    </div>
    <div class="triangle-mask">
        <a href="https://www.youtube.com/watch?v=d79nXbLUUh4"> <img src="\images\Ghost Town Neoni 2.jpg" alt=""></a>
    </div>
    <div class="upside-triangle-mask">
        <a href="https://www.youtube.com/watch?v=ErJjUbAPue0"> <img src = "\images\Loser Neoni.jpg" alt=""></a>
    </div>
</div>
<style>
    .container {
        display: flex;
        width: 80%;
        margin:auto;
        padding: 8px;
        justify-content: center;
    }
    .upside-triangle-mask {               
        min-width: 200px;
        display: flex;
        clip-path: polygon(50% 100%, 0 0, 100% 0);
        justify-content: center;        
    }
    /* put inside of a mdeia querie */
   
    .triangle-mask {        
        min-width: 200px;
        display: flex;
        clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
        justify-content: center;
    }
    img:hover {
        opacity: 0.7;
    }
   img {
    width: 100%;
   }
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
    .container {
        flex-direction: column;
    }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (max-width: 768px) {
    .container {
        flex-direction:column ;
    }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (max-width: 992px) {
    .upside-triangle-mask:nth-of-type(2n+3)
    {
        margin-left:-175px;
    }

    .triangle-mask:nth-of-type(2n+2)
    {
        margin-left:-175px;
    }

}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (max-width: 1200px) {
    .upside-triangle-mask:nth-of-type(2n+3)
    {
        margin-left:-185px;
    }

    .triangle-mask:nth-of-type(2n+2)
    {
        margin-left:-185px;
    }

}
/* Extra Extra large devices (large monitors, 1500ox and up) */
@media only screen and (max-width: 1500px) {
    .upside-triangle-mask:nth-of-type(2n+3)
    {
        margin-left:-245px;
    }

    .triangle-mask:nth-of-type(2n+2)
    {
        margin-left:-245px;
    }
}
</style> 