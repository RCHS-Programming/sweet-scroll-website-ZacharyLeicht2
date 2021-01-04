## Make your web page look great on mobile devices

A lot of people browse websites on their phones or tablets and not just on their computers. Therefore, is important to make sure that your web pages look great on the screens of all types of devices. The CSS ```@media``` rule helps you create web page designs that are **responsive** to the type of device the page is viewed on.

--- task ---

Some mobile devices have a problem with the parallax effect created by the CSS rule `background-attachment: fixed`. Add the following code to the end of your CSS file to turn off the parallax effect for mobile devices.

```css
/* Turn off parallax scrolling for tablets and phones as it is not supported */
@media only screen and (max-device-width: 1024px) {
    .cd-logo, .layer-cake, .kitchen-equipment, .cake-ingredients, .bowl-of-cakemix, .cake-in-oven, .decorated-cake {
        background-attachment: scroll;
    }
}
```

--- /task ---

--- collapse ---
---
title: More about the @media CSS rule
---

The `@media` rule lets you apply different styles to your web page depending on the type of device and the device's settings.

With the `@media` rule, you can check:
+ The width and height of the viewport
+ The width and height of the device
+ The orientation of the device (whether it is in landscape or portrait mode)
+ The screen resolution

`@media` is a great tool for creating tailored style sheets for screens of all sizes.

For more information on what you can do with the `@media` rule, see [dojo.soy/css_media_rule](http://dojo.soy/css_media_rule).

--- /collapse ---
