# smootherize
Make your scroll smooth.

## Preconditions
Add GSAP to your website (TweenMax or TweenLite)

## How to use
- Import smootherize.min.css and smootherize.min.js to your project
- Add a new div at the top of your content with the following class : 'sp-smootherizer'
- Add the following code to your main JS file : 

```javascript
let scroller = {
    target: document.querySelector(".container"),
    ease: 0.05,
    endY: 0,
    y: 0,
    resizeRequest: 1,
    scrollRequest: 0,
};

window.addEventListener("load", smootherize);
```

**target**: first child of 'sp-smootherizer'
**ease**: scroll speed

If you have any display issues, try to put sp-smootherizer in absolute position


## CDN
```
<link href="https://rawcdn.githack.com/vuetto/smootherize/851118376136daef128aa0a46c4d29de17eee145/smootherize.min.css" rel="stylesheet" type="text/css">
```
```
<script src="https://rawcdn.githack.com/vuetto/smootherize/851118376136daef128aa0a46c4d29de17eee145/smootherize.min.js"></script>
```
