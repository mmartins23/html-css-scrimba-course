# CSS Colors

In CSS, colors can be specified in several ways. Here are the different color formats commonly used in CSS along with code examples:

1. Keyword Color:
   CSS provides a set of predefined color keywords, such as `red`, `blue`, `green`, etc.

   ```css
   h1 {
     color: red;
   }
   ```

2. Hexadecimal Color:
   Hexadecimal colors are specified using a combination of six hexadecimal digits (0-9 and A-F), preceded by a hash symbol (#).

   ```css
   h2 {
     color: #336699;
   }
   ```

3. RGB Color:
   RGB colors are specified using the `rgb()` function, which takes three values for red, green, and blue channels. Each channel value ranges from 0 to 255.

   ```css
   p {
     color: rgb(255, 0, 128);
   }
   ```

4. RGBA Color:
   RGBA colors are similar to RGB colors, but with an additional alpha channel specifying the opacity. The alpha value ranges from 0 (fully transparent) to 1 (fully opaque).

   ```css
   span {
     color: rgba(0, 128, 0, 0.5);
   }
   ```

5. HSL Color:
   HSL (Hue, Saturation, Lightness) colors allow you to define a color based on its hue, saturation, and lightness values.

   ```css
   a {
     color: hsl(200, 100%, 50%);
   }
   ```

6. HSLA Color:
   HSLA colors are similar to HSL colors, but with an additional alpha channel for specifying opacity.

   ```css
   li {
     color: hsla(120, 100%, 50%, 0.7);
   }
   ```

7. Color Names:
   CSS also provides a list of named colors, such as `aliceblue`, `tomato`, `goldenrod`, etc.

   ```css
   body {
     background-color: papayawhip;
   }
   ```

Color values can be applied to various CSS properties, including `color`, `background-color`, `border-color`, and more. You can use colors to style text, backgrounds, borders, and other visual elements of your web page.

Remember that different browsers may display colors slightly differently, and it's important to consider accessibility and contrast when choosing colors for your designs.