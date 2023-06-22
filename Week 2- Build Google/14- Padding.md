# CSS Padding

![Padding CSS](https://blog.hubspot.com/hs-fs/hubfs/padding%20properties.jpg?width=1300&height=940&name=padding%20properties.jpg)

Padding in CSS is a property that defines the space between the content of an element and its border. It adds extra space inside the element, creating an internal space or buffer.

The `padding` property can be specified for all four sides of an element (top, right, bottom, and left), or individually using shorthand notation.

Here are a few examples of using padding in CSS:

1. Setting equal padding on all sides:
```css
.element {
  padding: 20px;
}
```

2. Setting different padding for each side:
```css
.element {
  padding-top: 10px;
  padding-right: 20px;
  padding-bottom: 15px;
  padding-left: 30px;
}
```

3. Using shorthand notation:
```css
.element {
  padding: 10px 20px 15px 30px; /* top, right, bottom, left */
}
```

You can also use percentage values or other CSS units (such as pixels or ems) to define the padding size.

Padding creates space between the content of an element and its border, pushing the content away from the edges. It helps control the spacing and layout of elements within a container, adding visual separation and improving readability.

Keep in mind that padding is included in the total size of the element, so it affects the overall dimensions of the box model.