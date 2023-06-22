# Flex-Direction

![Justify-content row](https://samanthaming.gumlet.io/flexbox30/9-flex-direction.jpg.gz)

***

In CSS, the `flex-direction` property is used to control the direction in which flex items are laid out within a flex container. It determines whether the flex items should flow horizontally or vertically.

The `flex-direction` property can be applied to a flex container, and it accepts the following values:

1. `row`: This is the default value. It lays out the flex items in a horizontal line, from left to right.

```css
.container {
  flex-direction: row;
}
```

2. `row-reverse`: It lays out the flex items in a horizontal line, but in reverse order, from right to left.

```css
.container {
  flex-direction: row-reverse;
}
```

3. `column`: It lays out the flex items in a vertical line, from top to bottom.

```css
.container {
  flex-direction: column;
}
```

4. `column-reverse`: It lays out the flex items in a vertical line, but in reverse order, from bottom to top.

```css
.container {
  flex-direction: column-reverse;
}
```

Here's an example of how you can use the `flex-direction` property with a flex container:

HTML:
```html
<div class="container">
  <div class="item">Item 1</div>
  <div class="item">Item 2</div>
  <div class="item">Item 3</div>
</div>
```

CSS:
```css
.container {
  display: flex;
  flex-direction: column;
}

.item {
  background-color: #f2f2f2;
  padding: 10px;
  margin: 5px;
}
```

In this example, the `flex-direction: column;` property is applied to the flex container with the class "container". This arranges the flex items in a vertical column, from top to bottom.

It's important to note that the `flex-direction` property affects the layout of flex items within the container, so it should be applied to the flex container itself. Additionally, other flex-related properties, such as `justify-content` and `align-items`, may need to be adjusted depending on the chosen `flex-direction` value to achieve the desired layout.