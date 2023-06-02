<script>

    import {songData} from "./songs.js";
    let songs = songData;
</script>


<h2>Neoni's Songs</h2>
<!--Set this to be a background image instead of a section, div, span, a href and an image-->
<section class="grid">
{#each songs as song}
        <div class="tooltip">
            <span class="tooltiptext">{song.name} by Neoni</span>
            <a href={song.link}> <img class="rcorners1"src={song.image.split("/revision")[0]} alt={song.name}></a>
        </div>
{/each}
</section>
<style>
  

.rcorners1 {
    border-radius: 25px;
    width: 100%;
    height: 100%;
}

.rcorners1:hover {
    opacity: 0.8;
}

.grid {
  display: grid;
	justify-content: center;
	justify-items: center;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}

.tooltip {
  position: relative;
  display: inline-block;
}

.tooltiptext {
  visibility: hidden;
  width: 30%;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 15px;
  padding: 5px 0;

  /* Position the tooltip */
  position: absolute;
  z-index: 1;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
}



/*Start of Media Queries*/
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .grid {
    grid-template-columns: 1fr;
  }
  .rcorners1 {

  }

} 

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
    .grid {
      grid-template-columns: 1fr 1fr;
    }
    .rcorners1 {
    
  }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {

.grid {
  grid-template-columns: 1fr 1fr ;
}
.rcorners1 {
    
  }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
.grid {
  grid-template-columns: 1fr 1fr 1fr;
}
.rcorners1 {
    
  }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .grid {
    grid-template-columns: 1fr 1fr 1fr 1fr;
  }
  .rcorners1 {
    width: 100%;
    height: 100%;
  }
}
/*End of Media Queries*/
</style>