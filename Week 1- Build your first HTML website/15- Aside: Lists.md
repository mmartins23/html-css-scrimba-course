# Lists

In HTML, the `<ul>` and `<ol>` elements are used to create lists. 

The `<ul>` element represents an unordered list, where the order of the list items doesn't matter. Each list item is marked with the `<li>` (list item) element. Here's an example:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

This will render as:

- Item 1
- Item 2
- Item 3

The `<ol>` element, on the other hand, represents an ordered list, where the order of the list items does matter. Like the `<ul>`, each list item is marked with the `<li>` element. Here's an example:

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ol>
```

This will render as:

1. First item
2. Second item
3. Third item

Both `<ul>` and `<ol>` can be nested to create sub-lists within a list. For example:

```html
<ul>
  <li>Item 1</li>
  <li>Item 2
    <ul>
      <li>Sub-item 1</li>
      <li>Sub-item 2</li>
    </ul>
  </li>
  <li>Item 3</li>
</ul>
```

This will render as:

- Item 1
- Item 2
  - Sub-item 1
  - Sub-item 2
- Item 3

The `<ul>` and `<ol>` elements provide a way to structure and present information in a list format, allowing for easy readability and organization of content on a webpage.