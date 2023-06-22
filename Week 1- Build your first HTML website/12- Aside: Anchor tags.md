# Aside: Anchor tags

![Anchor tags](https://qph.cf2.quoracdn.net/main-qimg-ac4b8105b4a26a3a65490aae4504a1bc)

The `<a>` element in HTML is used to create hyperlinks, allowing users to navigate to different web pages or sections within the same page. Here's an explanation of the `<a>` element with code examples:

```html
<a href="https://www.example.com">Link</a>
```
The `href` attribute specifies the URL or destination of the link. When the user clicks on the link, the browser navigates to the specified URL.

```html
<a href="#section">Jump to Section</a>
```
Instead of a full URL, the `href` attribute can also contain a fragment identifier (e.g., `#section`). In this case, clicking the link will scroll the page to the element with the corresponding ID (`<div id="section">...</div>`).

```html
<a href="mailto:info@example.com">Send Email</a>
```
The `href` attribute can also contain an email address prefixed with `mailto:`. When the user clicks on the link, it opens the default email client with a new email composition window, pre-filling the recipient address.

```html
<a href="tel:+1234567890">Call Us</a>
```
Similarly, the `href` attribute can contain a phone number prefixed with `tel:`. Clicking on the link initiates a phone call on devices with phone capabilities.

```html
<a href="#" onclick="alert('Clicked!')">Click Me</a>
```
The `href` attribute can also be set to `#` (hash symbol) or left empty to create a link that performs a JavaScript action or triggers an event. In this example, clicking the link triggers an alert.

The `<a>` element can also be used in combination with other elements, such as images or text, to create clickable elements. For example:

```html
<a href="https://www.example.com">
  <img src="image.jpg" alt="Image">
</a>
```
This code creates an image that serves as a clickable link to the specified URL.

Remember to use meaningful and descriptive anchor text for accessibility and user experience. Additionally, you can apply CSS styles to `<a>` elements to customize their appearance, such as changing the text color or adding hover effects.

These are just a few examples of how the `<a>` element can be used in HTML to create hyperlinks.