<button class="Btn" on:click={scrollToTop}>
    <div class="sign">&#x2B06</div>
    <div class="text">Back To Top</div>
</button>
<script>  
function scrollToTop() {
  window.scrollTo(0, 0);
}
</script>
<style>
/* Visual styling for the button */
.Btn {
  display: flex;
  position: fixed;
  bottom: 20px;
  right: 20px;
  align-items: center;
  width: 60px;
  height: 60px;
  border: none;
  border-radius: 50%;
  cursor: pointer;
  overflow: hidden;
  transition-duration: .3s;
  background-color: #ab3f00;
}

/* Visual stying for the up arrow sign  */
.sign {
    color: #ececec;
    width: 100%;
    transition-duration: .3s;
    font-size: 30px;
    text-shadow: 9px 6px 6px rgba(0,0,0,0.83);
}
/* Visual styling for the text that is displayed on the button */
.text {
  position: relative;
  right: 0%;
  width: 0%;
  opacity: 0;
  font-size: 1.2em;
  font-weight: 600;
  transition-duration: .3s;
  color: white;
  text-shadow: 9px 6px 6px rgba(0,0,0,0.83);
}
/* Changes the size of the button when the user hovers over the button */
.Btn:hover {
  background-color: #F28444;
  width: 125px;
  border-radius: 40px;
  transition-duration: .3s;
}
/* changes the text size when the user hovers over the button */
.Btn:hover .sign {
  width: 30%;
  transition-duration: .3s; 
  padding-left: 20px;
}
/* hover effect button's text */
.Btn:hover .text {
  opacity: 1;
  width: 70%;
  transition-duration: .3s;
  padding-right: 10px;
}

/* Turns the button off on smaller screens */
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .Btn {
    display: none;
  }
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
  .Btn {
    display: none;
  }
    
}
/* Shows the button on larger devices */
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .Btn {
  display: flex;
}
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
.Btn {
  display: flex;
}
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .Btn {
  display: flex;
}
}
/*End of Media Queries*/
</style>