# Web Fonts

Web-safe fonts, also known as system fonts or standard fonts, are fonts that are widely available across different operating systems and web browsers. These fonts are considered "safe" because they are typically installed on most devices and can be reliably rendered by web browsers, ensuring consistent typography across platforms.

Web-safe fonts provide a fallback option in case a specific font specified in the CSS is not available on the user's device. If the desired font is not present, the browser will automatically fall back to one of the web-safe fonts that are more likely to be available. This ensures that the content remains readable even if the desired font cannot be rendered.

Here are some commonly used web-safe fonts:

1. Arial
2. Helvetica
3. Times New Roman
4. Georgia
5. Courier New
6. Verdana
7. Tahoma
8. Trebuchet MS
9. Impact
10. Lucida Sans

To use web-safe fonts in CSS, you can specify the font stack, which is a list of fonts separated by commas. The browser will attempt to render the first font in the list, and if it's not available, it will move on to the next font in the stack until it finds a suitable fallback.

Here's an example of how to specify a font stack using web-safe fonts in CSS:

```css
body {
  font-family: Arial, Helvetica, sans-serif;
}
```

In this example, the `font-family` property specifies a font stack with Arial as the preferred font. If Arial is not available, the browser will attempt to render Helvetica, and if that's not available either, it will fall back to a generic sans-serif font.

It's important to note that web-safe fonts have limitations in terms of design and variety. If you want to use a specific font that is not web-safe, you can still do so by utilizing web font services like Google Fonts, Adobe Fonts, or self-hosting custom font files. These services provide a wider range of fonts that can be embedded into your web page using CSS `@font-face` rule.

However, if you prefer a simpler approach and want to ensure maximum compatibility and consistent typography across devices, web-safe fonts can be a reliable choice for your CSS font declarations.