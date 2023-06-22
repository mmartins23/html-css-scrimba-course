# CSS Borders

![Borders CSS](https://flaviocopes.com/images/css-border/Screen_Shot_2019-04-07_at_16.43.10.png)

***

![Border Radius CSS](https://css-irl.info/logical-border-radius-02.webp)

In CSS, the `border` property is used to define the border around an element, while the `border-radius` property is used to control the curvature or roundness of the corners. Here's an explanation of each property with code examples:

1. Border:
The `border` property allows you to define the width, style, and color of the border around an element. Here's an example that sets a solid black border with a width of 1 pixel:

```css
.element {
  border: 1px solid black;
}
```

You can also specify different values for the border width, style, and color individually. For example:

```css
.element {
  border-width: 2px;
  border-style: dashed;
  border-color: red;
}
```

2. Border-radius:
The `border-radius` property is used to control the curvature or roundness of the corners of an element. It accepts one or more values, specifying the radius for each corner. Here's an example that sets a border radius of 10 pixels for all corners:

```css
.element {
  border-radius: 10px;
}
```

You can specify different values for each corner by using the `border-radius` property with individual properties:

```css
.element {
  border-top-left-radius: 5px;
  border-top-right-radius: 10px;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 20px;
}
```

You can also use the `border-radius` property with percentage values or keywords like `50%` for a perfect circle.

Combined example using both `border` and `border-radius` properties:

```css
.element {
  border: 2px solid blue;
  border-radius: 10px;
}
```

These properties allow you to add visual styling to your elements by controlling the appearance of their borders and corners.