# HTML Nesting

Nesting in HTML refers to the practice of placing one HTML element inside another element. The `<div>` element is commonly used for nesting, as it serves as a generic container to group and organize other elements. Here are some code examples to illustrate the concept:

Example 1:
```html
<div>
  <h1>Welcome to My Website</h1>
  <p>This is the main content of the page.</p>
</div>
```
In this example, the `<h1>` and `<p>` elements are nested within the `<div>` element. The `<div>` acts as a container to group and structure the heading and paragraph elements together.

Example 2:
```html
<div class="container">
  <h2>About Me</h2>
  <p>I am a passionate web developer.</p>
</div>
```
Here, the `<h2>` and `<p>` elements are nested within a `<div>` element with the `class` attribute set to "container". This allows us to apply specific CSS styles or target this container element using JavaScript.

Example 3:
```html
<div>
  <img src="image.jpg" alt="Image">
  <div class="caption">A beautiful sunset</div>
</div>
```
In this example, an `<img>` element is nested within a `<div>` element. Additionally, a nested `<div>` with the class "caption" is used to provide a caption for the image. This allows for better organization and styling of the image and its associated content.

By using the `<div>` element for nesting, we can create structured layouts, group related content, apply styles, and manipulate elements using JavaScript. The choice of element for nesting may vary depending on the specific purpose and semantic meaning of the content being organized.