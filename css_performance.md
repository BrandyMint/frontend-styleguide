# Frontend tips


## CSS transforms

http://www.w3schools.com/cssref/css3_pr_transform.asp

http://www.paulirish.com/2012/why-moving-elements-with-translate-is-better-than-posabs-topleft/

## CSS transitions

http://www.w3schools.com/css/css3_transitions.asp

http://css3.bradshawenterprises.com/blog/jquery-vs-css3-transitions/

http://css-tricks.com/myth-busting-css-animations-vs-javascript/



## Force hardware acceleration

```
*
  -webkit-transform: translate3d(0px,0px,0px);
```

http://phonegap-tips.com/articles/force-hardware-acceleration-with-translate3d-sometimes.html

## Webkit font smoothing

```
// light text on dark background is blurred in webkit, there's a fix:
-webkit-font-smoothing: antialiased
```
http://phonegap-tips.com/articles/font-smoothing-and-css-transitions.html


## Mobile tips

```
// tap highlight color
*
  -webkit-tap-highlight-color: $color

// accelerated scrolling
.scrollable
  -webkit-overflow-scrolling: touch
  
// various fixes
*
  -webkit-touch-callout: none
  -webkit-text-size-adjust: none
  -webkit-user-select: none

```


Disable pinch and tap zoom:

```
<meta
  name="viewport"
  content="user-scalable=no, initial-scale=1, maximum-scale=1, minimum-scale=1, width=device-width, height=device-height, target-densitydpi=device-dpi" />
```
http://phonegap-tips.com/articles/disable-pinch-and-tap-zoom.html


## Image optimization

http://imageoptim.com/

https://github.com/toy/image_optim

https://github.com/plasticine/middleman-imageoptim

https://github.com/JamieMason/grunt-imageoptim

## Icon fonts

JUST FUCKING GOOGLE IT

## PNG & SVG sprites

http://compass-style.org/help/tutorials/spriting/


## Links

http://phonegap-tips.com/

http://www.onextrapixel.com/2012/05/03/css-tricks-how-to-speed-up-css-rendering/

http://csswizardry.com/2013/01/front-end-performance-for-web-designers-and-front-end-developers/

https://speakerdeck.com/jonrohan/githubs-css-performance

