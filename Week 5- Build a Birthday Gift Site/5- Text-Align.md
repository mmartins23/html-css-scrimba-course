# Text-align

![Text-align](https://udemy.benesse.co.jp/wp-content/uploads/text-align-2.png)

***

In CSS, the `text-align` property is used to control the horizontal alignment of text within an element. It determines how the text content should be positioned within the element's content box.

There are several values that can be used with the `text-align` property:

1. `left`: Aligns the text to the left edge of the element. This is the default value.

```css
.example {
  text-align: left;
}
```

2. `right`: Aligns the text to the right edge of the element.

```css
.example {
  text-align: right;
}
```

3. `center`: Centers the text within the element.

```css
.example {
  text-align: center;
}
```

4. `justify`: Adjusts the spacing between words so that the text aligns with both the left and right edges of the element. This is commonly used in paragraphs or blocks of text.

```css
.example {
  text-align: justify;
}
```

Here's an example of how you can apply the `text-align` property to a specific HTML element:

HTML:
```html
<div class="example">
  <h1>Welcome</h1>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
</div>
```

CSS:
```css
.example {
  text-align: center;
}
```

In this example, the text within the `<div>` element with the class "example" will be centered horizontally.

It's important to note that the `text-align` property affects only the direct text content within the element and does not apply to child elements. If you want to align child elements, you would need to apply the `text-align` property to the parent element.

Additionally, the `text-align` property can be overridden by more specific CSS selectors or cascading rules. So make sure to double-check your CSS rules and selectors to ensure the desired alignment is applied correctly.