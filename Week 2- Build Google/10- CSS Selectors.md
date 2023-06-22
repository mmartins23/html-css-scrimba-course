# CSS Selectors

![CSS Selectors](https://www.atatus.com/blog/content/images/size/w960/2023/01/css-selectors-1.png)

CSS selectors are used to target and select specific elements on a webpage for styling. They allow you to apply styles to elements based on their element type, attributes, relationships with other elements, and more. Here are some commonly used CSS selectors with code examples:

1. **Element Selector**: Targets elements based on their element type.

```css
p {
  color: blue;
}
```

The above selector targets all `<p>` elements on the page and applies a blue text color.

2. **Class Selector**: Targets elements based on their class attribute.

```css
.my-class {
  background-color: yellow;
}
```

The above selector targets all elements with the class "my-class" and applies a yellow background color.

3. **ID Selector**: Targets a specific element based on its ID attribute.

```css
#my-id {
  font-weight: bold;
}
```

The above selector targets the element with the ID "my-id" and applies a bold font weight.

4. **Attribute Selector**: Targets elements based on their attribute values.

```css
input[type="text"] {
  border: 1px solid black;
}
```

The above selector targets all `<input>` elements with the attribute `type="text"` and applies a black border.

5. **Descendant Selector**: Targets elements that are descendants of another element.

```css
ul li {
  color: green;
}
```

The above selector targets all `<li>` elements that are descendants of a `<ul>` element and applies a green text color.

6. **Adjacent Sibling Selector**: Targets an element that directly follows another element.

```css
h2 + p {
  font-size: 20px;
}
```

The above selector targets the `<p>` element that directly follows an `<h2>` element and applies a font size of 20 pixels.

7. **Pseudo-class Selector**: Targets elements based on a specific state or condition.

```css
a:hover {
  color: red;
}
```

The above selector targets `<a>` elements when they are being hovered over by the mouse and applies a red text color.

CSS selectors provide a powerful way to select and style specific elements on a webpage. By using different combinations of selectors, you can apply styles to targeted elements and create customized and visually appealing designs.