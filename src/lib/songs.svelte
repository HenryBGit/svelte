<script>
  import {songData} from "./songs.js";
  let songs = songData;

  songs.sort((a, b) =>  a.name.toUpperCase() < b.name.toUpperCase() ? -1 : 1);
</script>
<h2>Neoni's Songs</h2>
<section class="grid">
{#each songs as song}
      <div class="tooltip">
        <a class="hide" href="{song.link}">{song.name}</a> <!--Turns the image into text on phone view-->
          <span class="tooltiptext">{song.name} by Neoni</span>
          <a href={song.link}><img class="rcorners1"src={song.image.split("/revision")[0]} alt={song.name}> </a>
      </div>
{/each}
</section>
<style>
a {
  display: flex;
  color: white;
  text-decoration: none;
  justify-content: center;
}
a:hover{
  color:orange;
}
.grid {
display: grid;
overflow: hidden;
grid-template-columns: 1fr 1fr 1fr 1fr;
margin:auto;
}
.rcorners1 {
  border-radius: 25px;
}

.rcorners1:hover {
  opacity: 0.8;
}
.tooltip {
position: relative;
display: inline-block;
}

.tooltiptext {
visibility: hidden;
width: 40%;
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
  grid-template-columns: 1fr 1fr;
}
.rcorners1 {
  display: none;
  
}
.tooltiptext{
display: none;
}
a {
  font-size: 15px;
}
} 
/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
  .grid {
    grid-template-columns: 1fr 1fr;
  }
  .rcorners1 {
    display: none;
  }
  .tooltiptext {
    display:none;
  }
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
.grid {
  grid-template-columns: 1fr 1fr ;
}
.rcorners1 {
  display: flex;
  width: 100%;
  height: 100%;
}
.tooltiptext {
  display: block;
}
.hide {
  display: none;
}
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
.grid {
  grid-template-columns: 1fr 1fr 1fr;
  width: 80%;
}
.rcorners1 {
  display: flex;
  width: 100%;
  height: 100%;
}
.tooltiptext {
  display: block;
}
.hide {
  display: none;
}
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .grid {
    grid-template-columns: 1fr 1fr 1fr 1fr;
    width: 85%;
}
.rcorners1 {
  display: flex;
}
.tooltiptext {
  display: block;
}
.hide {
  display: none;
}
}
/*End of Media Queries*/
</style>