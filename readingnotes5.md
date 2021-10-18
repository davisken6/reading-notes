# CSS
**CSS** stands for **c**ascading **s**tyle **s**heets. This is what is used to personalize and decorate your webpage. HTML is the bones, CSS is the meat. With CSS, you can change the color and size of your text, add animation, create borders, change the font, and more. There are some rules, however, that you have to follow in order to achieve your desired results.

## Syntax
You first have to type your **selector**. This selects the HTML element you are styling. If you want your first header to be purple, you would enter 
"h1 {
    color: purple;
}"
The selector is "h1". Inside the curly braces is your **declaration**, to turn the color purple. "Color" is the **property**, and "purple" is the **value**. You can continue to use this format for your other headers and your paragraphs too.

### Inserting CSS
There are **3** ways to insert CSS. 
<ul>
<li><a>Internal CSS</a></li>
<li><a>External CSS</a></li>
<li><a>Inline CSS</a></li>
</ul>
**Internal style sheets** are used if one singular HTML page uses a unique style. This is defined in the "<style>" element, inside of the head section. 
**External style sheets** change the look of an entire website by changing one file. Each of these pages must include a reference to the external style sheet file inside of the "<link>" element, also inside of the head section.
**Inline style sheets** are used to apply a unique style for a **single** element. In order to use inline styles, you need to add the "<style>" attribute to the relevant element. Such as a header or a paragraph. 

### Cascading Order
HTML prioritizes certain styles before others. 

1. Inline Style

2. External and internal style sheets

3. Browser default