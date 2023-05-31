<script>

    import {songData} from "./songs.js";
    let songs = songData;
</script>

<!--Put into an excel doc and then read it from a json file-->
<h2>Neoni's Songs</h2>
{#each songs as song}
<div class="container">
    <section class="line">
        <div class="tooltip">
            <span class="tooltiptext">{song.name} by Neoni</span>
                <a href={song.link}> <img class="rcorners1"src={song.image.split("/revision")[0]} alt=""></a>
        </div>
    </section>
</div>
{/each}

<style>
.rcorners1 {
    border-radius: 25px;
    border: 2px solid transparent;
    width: 350px;
    height: 350px;
}

.rcorners1:hover {
    opacity: 0.8;
}

.line {
	display: flex;
	justify-content: center;
	justify-items: center;
}

.tooltip {
  position: relative;
  display: inline-block;
}

.tooltiptext {
  visibility: hidden;
  width: 120px;
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
</style>