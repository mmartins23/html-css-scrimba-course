# ID and Classes

![ID and Classes](https://i0.wp.com/css-tricks.com/wp-content/uploads/2021/04/classplusid.png?w=570&ssl=1)

In CSS, both IDs and classes are used as selectors to apply styles to HTML elements, but they have some differences in their usage and specificity. Let's explore the differences between IDs and classes in CSS:

1. IDs:
   - An ID is a unique identifier assigned to a specific HTML element.
   - IDs are denoted by the `id` attribute in HTML, and they should be unique within the entire document.
   - In CSS, IDs are selected using the `#` symbol followed by the ID name.
   - IDs have higher specificity than classes, meaning that styles applied to an ID selector will override styles applied to a class selector.
   - IDs are often used to target and style specific elements or apply JavaScript functionality.

   Here's an example of using an ID selector in CSS:

   ```html
   <h1 id="header">Hello, World!</h1>
   ```

   ```css
   #header {
     color: blue;
     font-size: 24px;
   }
   ```

   In this example, the styles defined in the `#header` ID selector will be applied to the `<h1>` element with the ID "header".

2. Classes:
   - A class is a reusable identifier that can be assigned to multiple HTML elements.
   - Classes are denoted by the `class` attribute in HTML, and multiple elements can have the same class.
   - In CSS, classes are selected using the `.` symbol followed by the class name.
   - Classes have lower specificity compared to IDs, so styles applied to a class selector can be overridden by styles applied to an ID selector.
   - Classes are commonly used to group and style similar elements or apply shared styles across multiple elements.

   Here's an example of using a class selector in CSS:

   ```html
   <p class="highlight">This text is highlighted.</p>
   <p class="highlight">So is this one.</p>
   ```

   ```css
   .highlight {
     background-color: yellow;
     color: black;
   }
   ```

   In this example, both `<p>` elements with the class "highlight" will have the defined background color and text color.

In summary, IDs are unique identifiers for individual elements, and classes are reusable identifiers that can be assigned to multiple elements. IDs have higher specificity and are used for unique styling or targeting specific elements, while classes are used for grouping and applying shared styles to multiple elements.