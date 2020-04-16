# Some notes

* CSS consists of two basic building blocks
    * Properties: These identifiers are readable by humans which are used for stylistic features, such as, font-size, width, background-color
    * Values: These specify the sytlistic feature of a given property.
* CSS declaration blocks define CSS Rulesets (CSS Rules) for a given selector, such as the two rules in the example below

```
h1 {
    color: blue;
    background-color: yellow;
}
```

* some examples of properties
    * font-size
        * font-size: 1.2em;
        * font-size: x-small;
        * font-size: 12px;
        * font-size: 80%;
    * width
        * width: 150px;
        * width: 20em;
        * width: auto;
    * background-color
        * background-color: brown;
        * background-color: #74992e;
        * background-color; rgb(255, 255, 254);
        * background-color; rgba(255, 255, 18, .5);  (a = alpha, i.e. transparency a=1.0 solid, a= 0 invisible)
        * background-color; hsl(50, 33%, 25%); (h = hue, s = saturation, l = lightness)
        * background-color; hsla(50, 33%, 25%, .75);
    * color
    * border
        * border: solid;
        * border: dashed red;
        * border: 1rem solid;
        * border: thick double #32a1ce;
        * border: 4mm ridge rgba(170, 50, 220, .6);
* some more properties
    * transform
        * transform: matrix(1, 2, 3, 4, 5, 6);
        * transform: translate(120px, 50%);
        * transform: scale(2, 0.5);
        * transform: skew(30deg, 20deg);
        * transform: scal(0.5) translate(-100%, -100%);
    * background-image
    * color
* @rules give CSS instruction about how to behave
    * @media, media queries apply to the CSS only when conditions apply that you've "baked in"
* shorthand properties
* comments are encouraged to be added to CSS to clarify
* whitespace is mainly for readability, the browser doesn't need it
* more properties
    * font-family
    * color
    * border-bottom
    * font-weight
    * font-size
    * text-decoration    
