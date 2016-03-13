a.clue
======
## A CSS library that links and anchors supplemented with icons
Fancy icons and symbols for your great web project.
Easy to use and uses the popular web font [FontAwesome](http://fortawesome.github.io/Font-Awesome/).

## How to use
Include the CSS in the \<head\> section in your HTML document.
```html
<!-- Import the FontAwesome CSS important for the icons and symbols -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/x.x.x/css/font-awesome.min.css" />
<!-- Import the a.clue CSS -->
<link rel="stylesheet" href="assets/css/aclue.min.css" />
<link rel="stylesheet" href="assets/css/yourown.css" />
```

You can overwrite the colors and style of all the icons in your own CSS file.
```css
/* Paint it black in yourown.css*/
ul.aclue > li > a[href]::before,
a[href]::after {
  color: #000;
}
```
Work also fine with Twitter [Bootstrap](http://getbootstrap.com/). The full list of icons and a real application see you in the demo on [CodePen](http://codepen.io/rrmelcer/pen/MyjpQK?editors=1100).

## License
```
/*
* ----------------------------------------------------------------------------
* "THE BEER-WARE LICENSE" (Revision 42):
* <raoul.rene.melcer@gmail.com> wrote this file. As long as you retain this
* notice you can do whatever you want with this stuff. If we meet some day,
* and you think this stuff is worth it, you can buy me a beer in return.
* Raoul René Melcer
* ----------------------------------------------------------------------------
*/
```
