# Images, Color, Text

 ### Adding images to web pages
 
Images are added to the HTML page using the <img> element. This element has no closing tag, elements with no closing tags are known as an empty elements. The element mainly carries the following attributes:

 (Links to an external site.)The source attribute src
It is used to specify the directory of the image, which can be:

The absolute URL of the image - if the image was taken from an online website

The Relative URL - if the image was uploaded from the device. The relative URL should be pointing to the directory of the image in the site's files.

 (Links to an external site.)The alternative text attribute alt
To provide a text description of the image. This will be helpful if the image was down or for people who can't see and use screen readers.

 (Links to an external site.)The title attribute
Too provide additional information about the image. This title will be displayed when the user hovers over the image.

Final Example:

__<img src="" title=""__

The < img> tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image

 ### Color Css:

** Rgb values:**
These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)

** Hex codes: **
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80

### Color names:
There are 147 predefined color names that are recognized by browsers. For example: DarkCyan

### Summary

Color not only brings your site to life, but also helps convey the mood and evokes reactions.
There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
Color pickers can help you find the color you want.
It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.

<img src="https://make.wordpress.org/core/files/2021/02/wordpress-admin-color-palette-WP57.png" title="">



### Text

<img src="https://cdn.educba.com/academy/wp-content/uploads/2019/08/CSS-Text-Formatting-Properties2.png" title="">



The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies. The value of this property is the name of the typeface you want to use.

font size : The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are:

pixels : Pixels are commonly used because they allow web designers very precise control over how much space their text takes up. The number of pixels is followed by the letters px.

percentages : The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px.

ems : An em is equivalent to the width of a letter m.

body { font-family: Arial, Verdana, sans-serif; font-size: 12px;} h1 { font-size: 200%;} h2 { font-size: 1.3em;}

The text-transform property : is used to change the case of text giving it one of the following values

uppercase
lowercase
capitalize
the font-style :

is used to create italic text, There are three values this property can take:

normal
italic
oblique .
