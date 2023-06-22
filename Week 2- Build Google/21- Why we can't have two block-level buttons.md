# Why we can't have two block-level buttons

In HTML and CSS, the primary reason why you can't have two block-level buttons side by side without additional styling is because block-level elements, by default, occupy the entire width of their container. This behavior causes them to stack vertically, one below the other.

A block-level element is an element that starts on a new line and takes up the full width available. Examples of block-level elements include `<div>`, `<p>`, and `<h1>` to `<h6>`. On the other hand, inline elements like `<span>`, `<a>`, and `<img>` do not create new lines and occupy only the necessary width to display their content.

To have two block-level buttons side by side, you would need to modify their default behavior by changing their display property or by using additional styling techniques. Here are a few options to achieve this:

1. Use inline-block: You can set the display property of the buttons to `inline-block` in CSS. This allows them to be treated as inline elements while still retaining some block-level properties, such as setting the width and height.

```html
<style>
  .button {
    display: inline-block;
    width: 150px;
    height: 40px;
    /* additional styling */
  }
</style>

<div>
  <button class="button">Button 1</button>
  <button class="button">Button 2</button>
</div>
```


2. Use flexbox: Flexbox is a CSS layout model that provides flexible ways to distribute space among elements. By using a flex container and setting appropriate flex properties, you can easily create side-by-side block-level buttons.

```html
<style>
  .button-container {
    display: flex;
    justify-content: space-between;
  }
  
  .button {
    width: 150px;
    height: 40px;
    /* additional styling */
  }
</style>

<div class="button-container">
  <button class="button">Button 1</button>
  <button class="button">Button 2</button>
</div>
```

These are just a few examples of how you can achieve side-by-side block-level buttons using different CSS techniques. The choice of which method to use depends on the specific requirements and constraints of your project.