# Web Developer Study
## 12 months web developer study. I decided to dedicate at least 12 months to learn web development.

![Begin Banner](/Documentation/top-1200x350.gif)

* Online courses, challenges and creation of my own projects.

## What I learned/used 
### CSS 
* Cascading Style Sheets (CSS) 
    * internal css
    * external css
    * link CSS file
    * mobile version -> < meta name="viewport" content="width=device-width, initial-scale=1.0" />
    * < article> -> article elements commonly contain multiple elements that have related information.
    * width
    * margin
    * padding
    * background-color
    * background-image
    * img 
    * display
    * class
    * id
    * Colors -> It's better practice to choose one color as the dominant color, and use its complementary color as an accent to bring attention to certain content on the page.
    * Colors
        * rgb
        * hex -> With hex colors, 00 is 0% of that color, and FF is 100%. So #00FF00 translates to 0% red, 100% green, and 0% blue, and is the same as rgb(0, 255, 0).
        * hsl -> The CSS hsl function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness.
        * rgba -> rgba(redValue, greenValue, blueValue, alphaValue);
        * gradient -> A gradient is when one color transitions into another. The CSS linear-gradient function lets you control the direction of the transition along a line, and which colors are used.
            * linear-gradient(gradientDirection, color1, color2, ...);
            * Color-stops allow you to fine-tune where colors are placed along the gradient line. They are a length unit like px or percentages that follow a color in the linear-gradient function.
        * opacity -> With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%
        * alpha channel -> alpha channel controls how transparent or opaque a color is. add an alpha channel to the other CSS color properties.
    * border
    * box-shadow -> property lets you apply one or more shadows around an element.
        * box-shadow: offsetX offsetY color;
        * blurRadius ->  box-shadow: offsetX offsetY blurRadius color;
        * spreadRadius -> box-shadow: offsetX offsetY blurRadius spreadRadius color;
    * form
        * label
        * input
        * required
        * minlength
        * pattern="[a-z0-5]{8,}"
    * pseudo-element
        * hover
        * active
        * visited
        * last-of-type
        * The ::after pseudo-element creates an element that is the last child of the selected element.
        * :not pseudo-selector can be used to select all elements that do not match the given CSS rule.
            * div:not(#example)

    * width of unset. -> This will remove the earlier rule which set all the input elements to width: 100%.
    * attribute selector -> selects an element based on the given attribute value
        * input[name="password"]
    * box-model -> In the CSS box model, every HTML element is treated as a box with four areas.
    * filter: blur()
    * transform
    * text-transform
    * flexbox -> Flexbox is a one-dimensional CSS layout that can control the way items are spaced out and aligned within a container.
        * Flexbox has a main and cross axis. The main axis is defined by the flex-direction property, which has four possible values:
            * row (default): horizontal axis with flex items from left to right
            * row-reverse: horizontal axis with flex items from right to left
            * column: vertical axis with flex items from top to bottom
            * column-reverse: vertical axis with flex items from bottom to top
        * The flex-wrap property determines how your flex items behave when the flex container is too small. Setting it to wrap will allow the items to wrap to the next row or column. nowrap (default) will prevent your items from wrapping and shrink them if needed.
        * The justify-content property determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them.
        * The align-items property positions the flex content along the cross axis. In this case, with your flex-direction set to row, your cross axis would be vertical.
        * object-fit: cover;
    * A useful property of an SVG (scalable vector graphics) is that it contains a path attribute which allows the image to be scaled without affecting the resolution of the resultant image.
        *   width:max(100px, 18vw);
    * The aspect-ratio CSS property sets a preferred aspect ratio for the box, which will be used in the calculation of auto sizes and some other layout functions.
    * min() / max() 
        * font-size: min(5vw, 1.2em);
        * width:max(100px, 18vw);
    * 
        






    

![End Banner](/Documentation/botton-1200x350.gif)