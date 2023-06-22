# Flex Item containers

![Flex Item Containers](https://sbsharma.com/wp-content/uploads/2020/05/flex-container-items.png)

***

In flexbox, the direct children of a flex container are called flex items. These are the elements that directly reside within the container element and are affected by the flexbox properties applied to the container.

Let's consider the following HTML structure:

```html
<div class="container">
  <div class="item">Item 1</div>
  <div class="item">Item 2</div>
  <div class="item">Item 3</div>
</div>
```

In this example, the `<div>` elements with the class "item" are the direct children of the flex container with the class "container". These "item" elements will be flex items affected by the flexbox properties applied to the container.

Now, let's see how we can use flexbox properties to control the layout and arrangement of these flex items.

![Box Model CSS](https://jogendras.files.wordpress.com/2019/02/flex-demo-direction.png)

***

1. Creating a Row Layout:

To create a row layout, where the flex items are displayed horizontally in a row, use the following CSS:

```css
.container {
  display: flex;
}
```

By default, the flex-direction property is set to "row", so the flex items will align horizontally.

2. Creating a Column Layout:

To create a column layout, where the flex items are displayed vertically in a column, you can add the flex-direction property set to "column":

```css
.container {
  display: flex;
  flex-direction: column;
}
```

3. Aligning Flex Items:

You can control the alignment of the flex items within the flex container using the align-items property:

```css
.container {
  display: flex;
  align-items: center;
}
```

This example centers the flex items vertically within the container.

4. Adjusting Flex Item Sizes:

You can use the flex property to control the sizes of the flex items relative to each other. The flex property takes a value that determines how much space each item should take up. For example:

```css
.item {
  flex: 1;
}
```

This will make all the flex items equally share the available space within the container.

These are just a few examples of how you can use flexbox properties to control the layout and appearance of the direct children (flex items) within a flex container. Flexbox provides numerous other properties, such as justify-content, align-self, flex-wrap, and more, to give you precise control over the flex items' positioning, alignment, and responsiveness.