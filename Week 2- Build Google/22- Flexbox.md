# Flexbox

![Flexbox](https://i.redd.it/rofzm44oka091.png)

Flexbox is a powerful layout module in CSS that provides a flexible way to create responsive and dynamic layouts. It allows you to easily align, distribute, and reorder elements within a container, making it ideal for building both simple and complex layouts.

To use flexbox, you need to define a flex container (the parent element) and apply specific properties to its child elements (flex items) to control their behavior and positioning.

Here are some key flexbox properties and their explanations:

1. `display: flex;`: This property is applied to the parent element to create a flex container. It enables flexbox behavior for its child elements.

2. `flex-direction`: Specifies the direction of the main axis, which determines how flex items are laid out within the container. It can take the following values:
   - `row`: Flex items are laid out horizontally in a row (default).
   - `column`: Flex items are laid out vertically in a column.
   - `row-reverse`: Flex items are laid out horizontally in a reversed order.
   - `column-reverse`: Flex items are laid out vertically in a reversed order.

3. `justify-content`: Defines the alignment of flex items along the main axis. It determines how extra space is distributed within the container. Common values include:
   - `flex-start`: Flex items are aligned to the start of the container (default).
   - `flex-end`: Flex items are aligned to the end of the container.
   - `center`: Flex items are centered within the container.
   - `space-between`: Flex items are evenly distributed with equal spacing between them.
   - `space-around`: Flex items are evenly distributed with equal spacing around them.

4. `align-items`: Controls the alignment of flex items along the cross axis. It specifies how flex items are positioned vertically within the container. Common values include:
   - `stretch`: Flex items are stretched to fill the container's height (default).
   - `flex-start`: Flex items are aligned to the start of the container.
   - `flex-end`: Flex items are aligned to the end of the container.
   - `center`: Flex items are centered vertically within the container.
   - `baseline`: Flex items are aligned based on their baseline.

5. `flex-grow`: Determines the ability of a flex item to grow in size to fill the available space. It specifies the ratio at which flex items grow relative to each other.

6. `flex-shrink`: Defines the ability of a flex item to shrink in size when there is not enough space available. It specifies the ratio at which flex items shrink relative to each other.

7. `flex-basis`: Specifies the initial size of a flex item before any remaining space is distributed. It can be set in absolute units like pixels (`px`) or as a percentage (`%`).

Now let's see an example of how to use flexbox:

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
  align-items: center;
}

.item {
  flex-grow: 1;
  flex-basis: 0;
  padding: 10px;
}
```

In this example, we have a parent container `<div class="container">` with three child elements `<div class="item">`. By applying `display: flex;` to the container, the child items become flex items. We use `justify-content: space-between;` to distribute the items evenly along the main axis with equal spacing between them. The `align-items: