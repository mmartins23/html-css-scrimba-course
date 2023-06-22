# justify-content property

`justify-content` is a CSS property that is used to control the alignment and spacing of flex items along the main axis of a flex container. It defines how the available space is distributed between the flex items.

![justify-content](https://samanthaming.gumlet.io/flexbox30/12-justify-content-row.jpg.gz?format=auto)

***

![justify-content](https://samanthaming.gumlet.io/flexbox30/13-justify-content-column.jpg.gz)

***

The `justify-content` property accepts various values that determine the positioning of flex items. Here are the different values and their effects:

1. `flex-start` (default): Flex items are packed towards the start of the flex container. They are aligned to the left side in a left-to-right language direction, or to the right side in a right-to-left language direction.

```css
.container {
  display: flex;
  justify-content: flex-start;
}
```

2. `flex-end`: Flex items are packed towards the end of the flex container. They are aligned to the right side in a left-to-right language direction, or to the left side in a right-to-left language direction.

```css
.container {
  display: flex;
  justify-content: flex-end;
}
```

3. `center`: Flex items are centered horizontally within the flex container.

```css
.container {
  display: flex;
  justify-content: center;
}
```

4. `space-between`: Flex items are evenly distributed along the main axis. The first item is placed at the start of the flex container, the last item is placed at the end, and the remaining items are spaced evenly between them.

```css
.container {
  display: flex;
  justify-content: space-between;
}
```

5. `space-around`: Flex items are evenly distributed along the main axis with equal space around them. The space between items is half the size of the space before the first item and after the last item.

```css
.container {
  display: flex;
  justify-content: space-around;
}
```

6. `space-evenly`: Flex items are evenly distributed along the main axis with equal space around them. The space between items and the space before the first item and after the last item are all equal.

```css
.container {
  display: flex;
  justify-content: space-evenly;
}
```

Here's an example that demonstrates the usage of `justify-content` with a flex container and multiple flex items:

```html
<div class="container">
  <div class="item">Item 1</div>
  <div class="item">Item 2</div>
  <div class="item">Item 3</div>
</div>
```

```css
.container {
  display: flex;
  justify-content: space-between;
}

.item {
  /* Additional styles for the flex items */
}
```

In this example, the flex container has `justify-content: space-between;` applied, which evenly spaces the flex items along the main axis, with the first item positioned at the start and the last item positioned at the end of the container.

You can experiment with different `justify-content` values and combine them with other flexbox properties to achieve the desired layout and spacing of flex items within a flex container.