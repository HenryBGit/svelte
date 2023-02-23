<style>

button {
    background-color: #e293b3;
    color:white;
}
button:hover{
    opacity: 0.7;
}
</style>
<script>

let count =0;
let point =0;
let reset =0;
function increment_count() {
    count++
    button_reset()
}

function button_reset(){
    if (count===6) {
        count=0
        reset++

    }
    points()

}
function points() {
    
        point++

}
</script>

<button on:click={increment_count}>
     
<h1> Clicked {count} {count===1? "time": "times"}</h1>

</button>

<p>You have {reset} {reset===1? "point": "points"}</p>

<body>

</body>