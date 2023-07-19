# Colored Markers

Colored Markers made using HTML & CSS.

This is the third project of **Responsive Web Design** course - https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-colors-by-building-a-set-of-colored-markers/.

This project mainly focuses on working with CSS colors.

## Learnings & Notes

- the title element gives search engines extra information about the page

- To tell browsers how to encode characters on your page, set the charset to utf-8. utf-8 is a universal character set that includes almost every character from all human languages.

- Each meta element adds information about the page that cannot be expressed by other HTML elements.

- If you add multiple classes to an HTML element, the styles of the first classes you list may be overridden by later classes.

- CSS rgb function -> background-color : rgb(0, 0, 0);

- RGB color wheel : https://www.w3schools.com/colors/colors_wheels.asp

- Two colors that are opposite from each other on the color wheel are called complementary colors. If two complementary colors are combined, they produce gray. But when they are placed side-by-side, these colors produce strong visual contrast and appear brighter. This contrast can be distracting if it's overused on a website, and can make text hard to read if it's placed on a complementary-colored background.

- It's better practice to choose one color as the dominant color, and use its complementary color as an accent to bring attention to certain content on the page.

- Hex color values start with a # character and take six characters from 0-9 and A-F. The first pair of characters represent red, the second pair represent green, and the third pair represent blue. For example, #4B5320.

- With hex colors, 00 is 0% of that color, and FF is 100%. So #00FF00 translates to 0% red, 100% green, and 0% blue, and is the same as rgb(0, 255, 0).

- The HSL color model, or hue, saturation, and lightness, is another way to represent colors.

The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.

If you imagine a color wheel, the hue red is at 0 degrees, green is at 120 degrees, and blue is at 240 degrees.

Saturation is the intensity of a color from 0%, or gray, to 100% for pure color. You must add the percent sign % to the saturation and lightness values.

Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral.

- A gradient is when one color transitions into another. The CSS linear-gradient function lets you control the direction of the transition along a line, and which colors are used.

linear-gradient(gradientDirection, color1, color2, ...);

One thing to remember is that the linear-gradient function actually creates an image element, and is usually paired with the background property which can accept an image as a value.

background: linear-gradient(90deg, red, green,blue);

-Color-stops allow you to fine-tune where colors are placed along the gradient line. They are a length unit like px or percentages that follow a color in the linear-gradient function.

https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient

linear-gradient(90deg, red 90%, black);

- Even without the color-stops, you might have noticed that the colors for the green marker transition at the same points as the red marker. The first color is at the start (0%), the second is in the middle (50%), and the last is at the end (100%) of the gradient line.

The linear-gradient function automatically calculates these values for you, and places colors evenly along the gradient line by default.

- If no gradientDirection argument is provided to the linear-gradient function, it arranges colors from top to bottom, or along a 180 degree line, by default.

-Opacity describes how opaque, or non-transparent, something is. For example, a solid wall is opaque, and no light can pass through. But a drinking glass is much more transparent, and you can see through the glass to the other side.

With the CSS opacity property, you can control how opaque or transparent an element is. With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%, the element will be completely opaque like it is by default.

- Another way to set the opacity for an element is with the alpha channel. Similar to the opacity property, the alpha channel controls how transparent or opaque a color is.

To add an alpha channel to an rgb color, use the rgba function instead.

The rgba function works just like the rgb function, but takes one more number from 0 to 1.0 for the alpha channel:

rgba(redValue, greenValue, blueValue, alphaValue);

- single border:

border-left-width: 10px;

border-left-style: solid;

border-left-color:black;

border-left: 10px solid black; (shorthand)

- The box-shadow property lets you apply one or more shadows around an element. Here is basic syntax:

box-shadow: offsetX offsetY color;

box-shadow: offsetX offsetY blurRadius spreadRadius color;
