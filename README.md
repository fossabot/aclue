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
Add the aclue class at the parent block element you want.
```html
<!-- for the whole document -->
<body class="aclue">
  Content with a <a href="https://www.linkedin.com/">Linkedin</a> link
  ...
<!-- or partial -->
  <h1 class="aclue">
    Title with a <a href="https://www.instagram.com/rrmelcer/">Instagram</a> link
  </h1>
<!-- or -->
  <div class="aclue">
    Div with a <a href="https://twitter.co/kubikpixel">Twitter</a> link
  </div>
<!-- or -->
  <p class="aclue">
    Paragraph with a <a href="https://www.facebook.com/kubikpixel/">Facebook</a> link
  </p>
<!-- or -->
  ...
</body>
```

You can overwrite the colors and style of all the icons in your own CSS file.
```css
/* Paint it black in yourown.css*/
ul.aclue > li > a[href]::before,
.aclue a[href]::after {
  color: #000;
}
```

Lists with icons you make it so easy
```html
<!-- add only the class "aclue" and finish is your iconic list -->
<ul class="aclue">
  <li><a href="https://twitter.com/kubikpixel/">Twitter</a>
  <li><a href="https://github.com/rrmelcer/">GitHub</a>
  <li><a href="http://codepen.io/rrmelcer/">CodePen</a>
  <li><a href="#">...</a>
<ul>
```
Work also fine with Twitter [Bootstrap](http://getbootstrap.com/). The full list of icons and a real application see you in the demo on [CodePen](http://codepen.io/rrmelcer/pen/MyjpQK?editors=1100).

## License
*"THE BEER-WARE LICENSE"* (Revision 42):
<raoul.rene.melcer@gmail.com> wrote this file. As long as you retain this
notice you can do whatever you want with this stuff. If we meet some day,
and you think this stuff is worth it, you can buy me a beer in return.
:beers: Raoul René Melcer
