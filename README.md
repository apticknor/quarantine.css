# quarantine.css

`quarantine.css` is a customizable micro library that provides predictability in your styles when user-authored HTML is added to a page (most likely via CMS or a WYSIWYG). This pattern works especially well when using a reset, and when specificity is kept low in your application's CSS.

## Installation

* [Bower](http://bower.io/): `bower install --save quarantine.css`
* [Download](http://github.com/apticknor/quarantine.css)

## Setup

Include the stylesheet on your document's `<head>`

```html
<link rel="stylesheet" href="quarantine.css">
```
or import the SASS file.

```css
@import "quarantine.scss";
```

Isolate the area where user-authored content will appear with a `<div>` that has a class of `quarantineContent`.

```html
<div class="quarantineContent">
    <!-- unpredictable html renders here -->
</div>
```

Edit styles within `quarantine.css` as needed to match your custom design.

## Browser Support

Quarantine uses CSS that will render properly in modern browsers including the latest release of Chrome, Firefox, Safari, and Opera, as well as support for IE9+.

## Demo

[Download the Demo](https://github.com/apticknor/quarantine.css/tree/master/demo) from GitHub
