<script>
document.addEventListener("DOMContentLoaded", function(){

const slider = document.querySelector(".custom-slider"); // .custom-slider use slider class on webflow defult slider
const slides = slider.querySelectorAll(".w-slide");

const left = slider.querySelector(".left-arrow"); // .left-arrow use left arrow class on webflow defult slider
const right = slider.querySelector(".right-arrow"); // .right-arrow use right arrow class on webflow defult slider

let current = 0;

function updateArrows(){

if(current === 0){
left.style.opacity="0.3";
left.style.pointerEvents="none";
}else{
left.style.opacity="1";
left.style.pointerEvents="auto";
}

if(current === slides.length-1){
right.style.opacity="0.3";
right.style.pointerEvents="none";
}else{
right.style.opacity="1";
right.style.pointerEvents="auto";
}

}

right.addEventListener("click",()=>{
if(current < slides.length-1){
current++
updateArrows()
}
})

left.addEventListener("click",()=>{
if(current>0){
current--
updateArrows()
}
})

updateArrows()

})
</script>
