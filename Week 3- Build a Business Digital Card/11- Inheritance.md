# CSS Inheritance

In CSS, inheritance refers to the process by which certain properties of an element are passed down from its parent element to its child elements. When a property is inherited, it means that the child elements will inherit the computed value of that property from their parent, unless explicitly overridden.

Not all CSS properties are inherited. Some properties, like `width` and `height`, are not inherited by default, while others, like `color` and `font-family`, are inherited. Whether a property is inherited or not is determined by the CSS specification.

Here's an example to illustrate how inheritance works in CSS:

HTML:
```html
<div class="parent">
  <p>This is the parent element.</p>
  <div class="child">
    <p>This is the child element.</p>
  </div>
</div>
```

CSS:
```css
.parent {
  color: blue;
  font-size: 20px;
}

.child {
  background-color: yellow;
}
```

In this example, the `.parent` element has the properties `color` and `font-size` set. The `.child` element is nested inside the parent and does not have any specific styles applied to it.

Since the `color` property is inherited, the `<p>` element inside both the parent and child elements will inherit the `color: blue;` value from the parent. Therefore, the text inside both `<p>` elements will be displayed in blue.

On the other hand, the `background-color` property is not inherited. So, while the `.child` element has a `background-color` set to yellow, the background color is not applied to the child's parent element or its `<p>` element.

It's important to note that the inheritance behavior may vary depending on the specific property and the browser's default styles. Additionally, you can use the `inherit` keyword to explicitly force an element to inherit a property value from its parent, even if the property is not inherited by default.

Overall, inheritance in CSS allows for efficient and consistent styling by propagating property values from parent elements to their child elements, reducing the need for repetitive styling declarations.