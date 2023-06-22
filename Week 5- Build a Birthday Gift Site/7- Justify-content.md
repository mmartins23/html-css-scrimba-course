# Justify-content

![Justify-content row](https://samanthaming.gumlet.io/flexbox30/12-justify-content-row.jpg.gz?format=auto)

![Justify-content column](https://samanthaming.gumlet.io/flexbox30/13-justify-content-column.jpg.gz?format=auto)

***

In CSS, the `justify-content` property is used to control the horizontal alignment of items within a flex container. It determines how the items should be positioned along the main axis of the flex container.

The `justify-content` property can be applied to a flex container, and it accepts the following values:

1. `flex-start`: This is the default value. It aligns the items to the start of the main axis.

```css
.container {
  justify-content: flex-start;
}
```

2. `flex-end`: Aligns the items to the end of the main axis.

```css
.container {
  justify-content: flex-end;
}
```

3. `center`: Centers the items along the main axis.

```css
.container {
  justify-content: center;
}
```

4. `space-between`: Distributes the items evenly along the main axis, with the first item at the start and the last item at the end. The spacing between the items is equal.

```css
.container {
  justify-content: space-between;
}
```

5. `space-around`: Distributes the items evenly along the main axis, with equal spacing around each item. The spacing between the items is twice as much as the spacing at the ends.

```css
.container {
  justify-content: space-around;
}
```

6. `space-evenly`: Distributes the items evenly along the main axis, with equal spacing between the items and at the ends.

```css
.container {
  justify-content: space-evenly;
}
```

Here's an example of how you can use the `justify-content` property with a flex container:

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
  justify-content: space-between;
}

.item {
  background-color: #f2f2f2;
  padding: 10px;
  margin: 5px;
}
```

In this example, the `justify-content: space-between;` property is applied to the flex container with the class "container". This evenly distributes the items along the main axis, with the first item at the start and the last item at the end. The `display: flex;` property is also set on the container to make it a flex container.

It's important to note that the `justify-content` property is specific to flex containers. It only affects the direct child items within the container and does not apply to elements outside of the flex container. Additionally, the `justify-content` property can be overridden by other CSS rules or cascading styles, so make sure to check your CSS specificity and cascade order if you encounter unexpected results.