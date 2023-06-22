# Align-items

![Align-items row](https://samanthaming.gumlet.io/flexbox30/15-align-items-row.jpg.gz)

![Align-items column](https://samanthaming.gumlet.io/flexbox30/17-align-items-column.jpg.gz?format=auto)

***

In CSS, the `align-items` property is used to control the vertical alignment of items within a flex container. It determines how the items should be positioned along the cross-axis of the flex container.

The `align-items` property can be applied to a flex container, and it accepts the following values:

1. `stretch`: This is the default value. It stretches the items to fill the cross-axis of the flex container.

```css
.container {
  align-items: stretch;
}
```

2. `flex-start`: Aligns the items to the start of the cross-axis.

```css
.container {
  align-items: flex-start;
}
```

3. `flex-end`: Aligns the items to the end of the cross-axis.

```css
.container {
  align-items: flex-end;
}
```

4. `center`: Centers the items along the cross-axis.

```css
.container {
  align-items: center;
}
```

5. `baseline`: Aligns the items along their baselines. The baseline is the imaginary line on which the text sits.

```css
.container {
  align-items: baseline;
}
```

Here's an example of how you can use the `align-items` property with a flex container:

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
  align-items: center;
  height: 200px; /* Specify a height to see the effect */
}

.item {
  background-color: #f2f2f2;
  padding: 10px;
  margin: 5px;
}
```

In this example, the `align-items: center;` property is applied to the flex container with the class "container". This centers the items vertically within the container. The `height` property is also set on the container to create a visible area for the items.

It's important to note that the `align-items` property is specific to flex containers. It only affects the direct child items within the container and does not apply to elements outside of the flex container. Additionally, the `align-items` property can be overridden by other CSS rules or cascading styles, so make sure to check your CSS specificity and cascade order if you encounter unexpected results.