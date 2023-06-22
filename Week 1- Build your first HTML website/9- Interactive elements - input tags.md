# Interactive elements - input tags

Certainly! The `<input>` element in HTML supports various types that determine the behavior and input format of the form control. Here's an explanation of some commonly used `<input>` types with code examples:

1. Text Input:
```html
<input type="text" name="username" placeholder="Enter your username">
```
The `text` type creates a basic text input field where users can enter alphanumeric characters.

2. Password Input:
```html
<input type="password" name="password" placeholder="Enter your password">
```
The `password` type masks the entered characters, commonly used for password inputs to keep the input hidden.

3. Email Input:
```html
<input type="email" name="email" placeholder="Enter your email">
```
The `email` type enforces email validation, ensuring that the entered value follows the email format.

4. Number Input:
```html
<input type="number" name="quantity" min="1" max="10">
```
The `number` type restricts input to numeric values and provides increment and decrement controls. The `min` and `max` attributes define the range of allowed values.

5. Checkbox:
```html
<input type="checkbox" id="checkbox1" name="option1" value="1">
<label for="checkbox1">Option 1</label>
```
The `checkbox` type allows users to select or deselect an option. Multiple checkboxes can be grouped together using the same `name` attribute.

6. Radio Buttons:
```html
<input type="radio" id="radio1" name="gender" value="male">
<label for="radio1">Male</label>
<input type="radio" id="radio2" name="gender" value="female">
<label for="radio2">Female</label>
```
The `radio` type allows users to choose only one option from a group. All radio buttons in the group share the same `name` attribute but have different `id` values.

7. File Upload:
```html
<input type="file" name="myfile">
```
The `file` type creates a file upload control that allows users to select and upload files from their device.

These are just a few examples of the `<input>` types available in HTML. Other types include `date`, `time`, `color`, `range`, `search`, and more. Each type has its own specific behavior and input format, providing different options for capturing user input in forms.

Remember to always validate and sanitize user input on the server-side to ensure data integrity and security.