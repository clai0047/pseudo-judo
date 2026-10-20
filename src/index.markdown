<main class="container">
 <button id="ninja" class="ninja"><img src="https://imdac.github.io/images/codepen/ninja.svg"></button>
  <div id="controls" class="controls">
    <button id="spin" class="btn">Spin</button>
    <button id="flip" class="btn">Flip</button>
    <button id="grow" class="btn">Grow</button>
    <button id="shrink" class="btn">Shrink</button>
    <button id="special" class="btn">Special</button>
  </div>
</main>
<div class="instructions">

## Pseudo Judo

Use pseudo classes, the transition and the transform properties to animate the ninja's actions
  
1. When mousing over the ninja, make him quickly fade out to near invisibility using `opacity` add `transition` properties and the `:hover` pseudo class on the `.ninja` class.<br>*Example:* `.ninja:hover { opacity: 0.1; transition: 0.3s; }`
2. When mousing out of the ninja, make him slowly return to normal visibility using the `transition` property on the `.ninja` class.
3. When clicking on the ninja, make him quickly jump and remain in the air using the `transform` and `transition` properties and the `:active` pseudo class on the `.ninja` class.
4. When clicking the spin button, make the ninja spin on the vertical (y) axis by using the `transform` and `transition` properties on the `.spin` class. 
5. When clicking the flip button, make the ninja spin on the horizontal (x) axis by using the `transform` and `transition` properties on the `.flip` class. 
6. When clicking the grow button, make the ninja grow to twice his normal size by using the `transform` and `transition` properties on the `.grow` class. 
7. When clicking the shrink button, make the ninja shrink to half his normal size by using the `transform` and `transition` properties on the `.shrink` class.
8. When clicking the special button, make the ninja do his "special" move. You decide what that is by applying different properties to the `.special` class.
  
