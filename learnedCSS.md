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
    * The clip property lets you specify a rectangle to clip an absolutely positioned element. The rectangle is specified as four coordinates, all from the top-left corner of the element to be clipped.
        * Note: The clip property does not work if "overflow:visible".
        * Note: The clip property is deprecated and will be replaced by the clip-path property in the future.



    * selector Includes
        * span[class~="sr-only"] -> all span tag that has the sr-only class in it.
    * clip -> The clip CSS property defines a visible portion of an element. The clip property applies only to absolutely positioned elements — that is, elements with position:absolute or position:fixed.
        * clip: rect(1px, 1px, 1px, 1px)
    * Clip-path -> The clip-path property determines the shape the clip property should take. -> The clip-path CSS property creates a clipping region that sets what part of an element should be shown. Parts that are inside the region are shown, while those outside are hidden.
    * white-space -> The white-space CSS property sets how white space inside an element is handled.
    * calc() ->The calc() CSS function lets you perform calculations when specifying CSS property values. It can be used anywhere a <length>, <frequency>, <angle>, <time>, <percentage>, <number>, or <integer> is allowed. --> The calc() function is a CSS function that allows you to calculate a value based on other values. For example, you can use it to calculate the width of the viewport minus the margin of an element:
    * position absolute
    * z-index
    
    * html{font-size:62.5%;} This will set the default font size for your web page to 10px (the browser default is 16px). 

    * object-fit: The object-fit property tells the browser how to position the element within its container. In this case, cover will set the image to fill the container, cropping as needed to avoid changing the aspect ratio.


    * Animation
        * transform-origin => property is used to set the point around which a CSS transformation is applied. For example, when performing a rotate, the transform-origin determines around which point the element is rotated.
        * @keyframes => The @keyframes at-rule is used to define the flow of a CSS animation. Within the @keyframes rule, you can create selectors for specific points in the animation sequence, such as 0% or 25%, or use from and to to define the start and end of the sequence.
        * animation-name => The animation-name property is used to link a @keyframes rule to a CSS selector. The value of this property should match the name of the @keyframes rule.
        * animation-duration => The animation-duration property is used to set how long the animation should sequence to complete. The time should be specified in either seconds (s) or milliseconds (ms).
        * animation-iteration-count => The animation-iteration-count property sets how many times your animation should repeat. This can be set to a number, or to infinite to indefinitely repeat the animation.
        * animation-timing-function  => The animation-timing-function property sets how the animation should progress over time. There are a few different values for this property
        * ease-in-out => the ease-in-out timing function setting will tell the animation to start and end at a slower pace, but move more quickly in the middle of the cycle.

    * transform shapes
        * skew => the skew transform function, which takes two arguments. The first being an angle to shear the x-axis by, and the second being an angle to shear the y-axis by.





    

![End Banner](/Documentation/botton-1200x350.gif)