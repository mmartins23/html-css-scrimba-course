# CSS :hover Pseudo Class

In CSS, the `:hover` pseudo-class is used to apply styles to an element when it is being hovered over by the user. It allows you to change the appearance of an element dynamically when the user interacts with it.

To use the `:hover` pseudo-class, you simply add it to the CSS selector of the element you want to target. Here's an example:

HTML:
```html
<button class="my-button">Hover Me</button>
```

CSS:
```css
.my-button:hover {
  background-color: blue;
  color: white;
}
```

In this example, when the user hovers over the button element with the class "my-button", the background color is changed to blue and the text color is changed to white.

You can apply any valid CSS property and value within the `:hover` pseudo-class to modify the element's appearance. This includes properties like background-color, color, font-size, border, and more. Here's another example:

HTML:
```html
<a class="my-link" href="#">Hover Me</a>
```

CSS:
```css
.my-link:hover {
  text-decoration: underline;
  color: red;
}
```

In this example, when the user hovers over the link element with the class "my-link", the text is underlined and the color is changed to red.

The `:hover` pseudo-class can be used with any HTML element, such as buttons, links, images, or any other element that can receive user interaction. It provides a way to add interactivity and visual feedback to your website or application.

It's important to note that the `:hover` pseudo-class is specific to mouse-based interactions and may not be applicable or behave as expected on touch-enabled devices.