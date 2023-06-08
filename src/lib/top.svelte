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
.Btn {
  right: 0px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  width: 60px;
  height: 60px;
  border: none;
  border-radius: 50%;
  cursor: pointer;
  position: relative;
  overflow: hidden;
  transition-duration: .3s;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.199);
  background-color: #ab3f00;
}

/* up arrow sign */
.sign {
    color: #ececec;
    width: 100%;
    transition-duration: .3s;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 30px;
}
.text {
  position: relative;
  right: 0%;
  width: 0%;
  opacity: 0;
  color: white;
  font-size: 1.2em;
  font-weight: 600;
  transition-duration: .3s;
}
/* hover effect on button width */
.Btn:hover {
  background-color: #F28444;
  width: 125px;
  border-radius: 40px;
  transition-duration: .3s;
  transform: 0.4s cubic-bezier(0.3, 1, 0.8, 1);
}

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
/* button click effect*/
.Btn:active {
  transform: translate(2px ,2px);
}
</style>