# svg-icons
Clean, simplified, and optimized company logos and user interface icons.

I take pride in coding simplified shapes. Unifying (merging) paths that don't requires to be individual by design.

## Technical details

* **`*-color`** : These are brands official colors. Most are are more complexe XML files; They have multiple paths and many have more then one colors. I try to manage color values via **CSS classnames** so we can access theire `fill` values from an external stylesheet.
* **Monochrome icons** : These are coded with `style="fill:currentColor"` so you don't need to edit their code to adjust the color. To apply a custom color simply set the CSS text `color` attribute on the parent container so the child icon will inherit that color value. _Read more about CSS keyword_ [`currentColor`](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/color_value#currentcolor_keyword).
* **`data-author`** : I use this attribute to inform **who designed it** and, when relevant, the original names when from the library so you can find it if you ever need to.
* **Dimensions** :
   * **`box24`** : This suffix indicates an icon optimized for a **square aspect-ratio** that displays by default to 24x24 pixels  (`viewBox="0 0 24 24"`).
   * **20x20 inner area** : Like for Google Material Icons, the main area of the image itself is _more or less_ 20x20 (pixels) so they all look the same regardless of their shapes. 

## Repositories

1. [icon-brand-box24/](/icon-brand-box24/)
   > Original logos are either downloaded from [Commons.WikiMedia.org](https://commons.wikimedia.org/) or from the officials websites of the brands.
1. [icon-ui-box24/](/icon-ui-box24/)
   > Somes are duplicatas from Material Symbols that I simply optimized and renamed for my convinience.


&nbsp;
