# Design with CSS
[Good resource from W3Schools](https://www.w3schools.com/css/default.asp)

## Cascading Style Sheet (CSS)

- Box model

    - Content
    - Padding
    - Border
    - Margin

- CSS allows you to create rules that control the way each individual box (and the content of that box) is presented.

- The browser reads CSS from top to bottom. If the same selector is added twice, the rule for the last one listed will be used.

- `p {font-family: Arial;}`

    - p is the selector
    - font-family: Arial; is the declaration
    - font-family: is the property
    - Arial; is the value
    - selector {property: value;} - this is the rule set format
    - must end each declaration with a semi-colon (;)
    - can have multiple declarations within a rule set

- Can put CSS in the HTML file or in a separate file

    - Benefit of a separate file is that different pages can use the same style sheet and you only have to maintain the styles in one place
    - You can have multiple style sheets.

- How the CSS rules cascade

    - The browser reads CSS from top to bottom.  
    - Last rule - if selectors are identical, the last one listed takes precedence
    - Specificity - if one selector is more specific than another, the more specific one will take precedence

        - h1 is more specific than *
        - p b is more specific than p
        - p#intro is more specific than p
    - Important - if you add !important after any property value, then if will always be considered more important than other rules that apply to the same element

- Inheritance

    - body element rules apply to most child elements
    - background and border properties are not inherited
    - use inherit for the value of the property to force a child to inherit from the parent

## Ways to specify color

- RGB values

    - rgb(red, green, blue)
    - rgb(255,99,71)
- Hex values

    - #ff6347
- Color name

    - Tomato

- HSL

    - Hue, Saturation, Lightness
    - Lightness: 0% is white, 50% is normal, 100% is black
    - hsl(9,100%,64%)

- HSLA and RGBA

    - A is Alpha. It's a number between 0 and 1.0 that represents transparency. 0.5 is 50% transparency.
    - rgba(255, 99, 71, 0.5)
    - hsla(9, 100%, 64%, 0.5)

- Older browsers may not support hsl or hsla. In this case, you should add another rule before the hsl or hsla one that uses a different option.


---
[Home page](https://marlene-rinker.github.io/learning-journal/)
