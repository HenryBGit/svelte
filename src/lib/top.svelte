<section class="right">
<button class="Btn" on:click={scrollToTop}>
    <div class="sign">&#x2B06</div>
    <div class="text">Back To Top</div>
</button>
</section>
<script>  
function scrollToTop() {
  window.scrollTo(0, 0);
}
</script>
<style>
.right {
  padding-right: 15px;
  padding-bottom: 7px;
  display: flex;
  justify-content: right;
}
/* Visual styling for the button */
.Btn {
  position: sticky;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  width: 60px;
  height: 60px;
  border: none;
  border-radius: 50%;
  cursor: pointer;
  overflow: hidden;
  transition-duration: .3s;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.199);
  background-color: #ab3f00;
}

/* Visual stying for the up arrow sign  */
.sign {
    color: #ececec;
    width: 100%;
    transition-duration: .3s;
    display: flex;
    align-items: center;
    justify-content: center;
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
/* Button click effect */
.Btn:active {
  transform: translate(2px ,2px);
}
</style>