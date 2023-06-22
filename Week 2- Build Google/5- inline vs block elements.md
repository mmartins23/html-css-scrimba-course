# Inline vs Block elements

![Block and Inline CSS](https://media.gcflearnfree.org/content/5e82363212da9215e057b928_03_30_2020/block_vs_inline_diagram.png)

![Block and Inline CSS](https://dotnettutorials.net/wp-content/uploads/2021/11/word-image-453.png)


In CSS, the terms "block" and "inline" refer to two different display properties that elements can have. These properties determine how elements are visually displayed and how they interact with other elements on the webpage.

1. Block-level Elements:
Block-level elements are displayed as individual blocks that occupy the entire width of their parent container by default. They start on a new line and stack vertically on top of each other. Block-level elements are used for structural elements like paragraphs, headings, dividers, and sections.

Example:
```html
<div>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
  <ul>
    <li>List item 1</li>
    <li>List item 2</li>
  </ul>
</div>
```

In the above example, the `<div>`, `<h1>`, `<p>`, and `<ul>` elements are block-level elements. Each of these elements occupies its own block and is displayed on a new line.

2. Inline Elements:
Inline elements, on the other hand, do not start on a new line and flow alongside neighboring elements. They only occupy the space necessary to hold their content. Inline elements are used for small-scale elements within a block of text or for elements that don't require their own line.

Example:
```html
<p>This is an <span>inline</span> element.</p>
<a href="#">This is an inline link</a>
```

In the above example, the `<span>` and `<a>` elements are inline elements. They do not create new lines and flow within the text content.

Difference:
The main difference between block-level and inline elements is their default behavior in terms of layout. Block-level elements start on a new line and occupy the full width available, while inline elements do not start on a new line and only take up the necessary space.

It's worth noting that the display property of elements can be modified using CSS to change their behavior. For example, you can set an inline element to display as a block-level element and vice versa using the `display` property.

```css
span {
  display: block; /* Changes an inline element to a block-level element */
}

div {
  display: inline; /* Changes a block-level element to an inline element */
}
```

By modifying the display property, you can control the layout and positioning of elements on the webpage.