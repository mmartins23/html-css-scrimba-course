# Interactive elements - button

The `<button>` element in HTML is used to create a clickable button on a web page. It is often used to trigger an action or perform a specific function when clicked. Here's an explanation of the `<button>` element with some code examples:

Example 1: Basic Button
```html
<button>Click Me</button>
```
In this simple example, we have a `<button>` element with the text "Click Me". When this button is clicked by a user, it can trigger JavaScript code or perform a default action associated with it.

Example 2: Button with Type Attribute
```html
<button type="submit">Submit Form</button>
```
In this example, the `<button>` element has the `type` attribute set to "submit". This is commonly used within a `<form>` element to submit the form data to the server when the button is clicked. The `type` attribute can also have other values such as "reset" or "button", each serving a different purpose.

Example 3: Button with Event Handler
```html
<button onclick="myFunction()">Click Me</button>
<script>
  function myFunction() {
    alert("Button Clicked!");
  }
</script>
```
In this example, the `<button>` element has an `onclick` attribute that specifies a JavaScript function to be executed when the button is clicked. When the button is clicked, the `myFunction()` function is called, which displays an alert message saying "Button Clicked!".

The `<button>` element can also be styled using CSS to change its appearance, such as background color, font size, and padding, among other properties. Additionally, you can use CSS classes and JavaScript to manipulate the button's behavior and appearance dynamically.

Overall, the `<button>` element is a versatile element in HTML that allows you to create interactive and clickable buttons on your web page, providing a way for users to interact with your website's functionality.