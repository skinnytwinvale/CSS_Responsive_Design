# CSS_Responsive_Design

## CSS Resets
This is just a stylesheet which attempts to overwrite (or reset) any default browser styles with styling that will then be the same across different environments.

1. reset.css

2. normalize.css

## Responsive Design

One thing to keep in mind is how your site looks on different devices. You might spend days meticulously crafting a beautifully designed site on your laptop, only to discover that it looks like garbage on your phone.

Responsive design is a way to approach designing your applications that is mindful of the fact that users don't all have screens of the same size. With a responsive design, the goal is to make your site beautiful for users on a variety of devices, while minimizing the amount of CSS you need to write.

One of the fundamental building blocks of responsive design along with mobile first design is the ability to show different styles for different conditions. As with keyframes, media queries are declared using an at- rule. Here's a simple example of the syntax:

@ media screen and (max-width: 480px) {
    /* add some styles for a mobile device here*/
}

## Responsive Unit

When it comes to setting widths, font sizes, or other things require some measurement of length, we've seen two different units of measurement: pixels and percentages

Pixels are an absolute unit of measurement. This means that they are great when you know "exactly" what the dimensions for the property you're setting should be. Pixels, inches, centimeters, millimeters, and points are all examples of absolute units of measurement.

In contrast, relative units, like the name suggests, are always relative to the length of another property. Examples here include percentages, ems, root ems, exes, character units, viewport width, viewport height, viewport minimum, and viewport maximum.


- % - As we've seen, this sets the length to be a percentage of whatever container or fixed value the element is inside of.
- em - 1em is equal to the default font-size for the element. This lets you set properties involving length relative to this font size. Note that if you define the font-size in terms of ems, 1em will correspond to the font-size of the parent.
- rem - just like em's but they are only relative to the root (i.e. html) element. This means that 1rem corresponds to the same size everywhere on the page.
- vh - 1vh is equal to 1/100th of the viewport's height.
- vw - 1vw is equal to 1/100th of the viewport's width. 
- vmin - 1vmin is equal to the minimum of 1vh and 1vw. 
- vmax - 1vmax is equal to the maximum of 1vh and 1vw.
