# 6. HTML: COLORS

*  In Html, colors are specified with their predefined names or with their specific values like: RGB, CMYK, HSL, etc.

### But how do we add color to the elements?

* HTML supports about 140 standard color names but throught style attributes we can change the color of the elements, this could be simply done by using their standard names as values or using the HSL, HSV, RGB, CMYK, etc. color values. 

## Through attributes

we can add color in html through the following attribute properties:

### Background color `"background-color"`
In HTML, we can set the background color of the HTML elements:

```
background-color: red;
```
Example: 

```
<p style="background-color:red;">Hello World!</p>
```

### Text color `"color"`
In HTML, we can set the text color of the HTML elements:

```
color: red;
```
Example: 

```
<p style="color:red;">Hello World!</p>
```

### Border color `"border-color"`
We can also set the border color of the HTML elements:

```
border-color: red;
```
Example: 

```
<p style="border-color:red;">Hello World!</p>
```

## Through color values

Colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.

### RGB values

In HTML, a color can be specified as an RGB value, An RGB color value represents RED, GREEN, and BLUE light sources (in case of RGBA "A" stands for alpha that handles the opacity).

Formula:

```
rgb(red, green, blue);
```

Each parameter (red, green, and blue) defines the intensity of the color with a value between 0 and 255.

### HEX values

in HEX color value, a color is specified using a hexadecimal value form `#rrggbb`

Here, rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

### HSL values

HSL stands for hue, saturation, and lightness. HSLA color values are an extension of HSL with an Alpha channel (opacity).

Here, Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue. Saturation is a percentage value. 0% means a shade of gray, and 100% is the full color. Lightness is also a percentage value. 0% is black, and 100% is white.

