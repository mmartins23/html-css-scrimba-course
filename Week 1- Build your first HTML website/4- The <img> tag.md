# The `<img>` tag

![Image Tag](https://cdo-curriculum.s3.amazonaws.com/media/uploads/img_tag.png)

The HTML `<img>` tag is used to insert an image into a webpage. It allows you to display images on your website and control various aspects such as size, alignment, and alternative text. Here's an explanation of the `<img>` tag with code examples:

The basic syntax of the `<img>` tag is as follows:
```html
<img src="image-url" alt="alternative-text" width="image-width" height="image-height">
```

- `src`: This attribute specifies the source URL of the image. It can be an absolute URL or a relative path to the image file.
- `alt`: This attribute provides alternative text for the image. It is displayed when the image cannot be loaded or for accessibility purposes. It should describe the content or purpose of the image.
- `width` and `height`: These attributes define the width and height of the image in pixels. They are optional but recommended to set, as they help the browser allocate space for the image before it loads, improving page layout.

Example 1: Inserting an image from a URL:
```html
<img src="https://example.com/image.jpg" alt="Image description" width="300" height="200">
```

Example 2: Inserting an image from a local file (relative path):
```html
<img src="images/image.jpg" alt="Image description" width="300" height="200">
```

In addition to these basic attributes, there are several other attributes you can use with the `<img>` tag:

- `title`: This attribute specifies a tooltip or additional information that is displayed when the user hovers over the image.
- `class` and `id`: These attributes can be used to apply CSS styles or select the image element with JavaScript.
- `style`: This attribute allows you to define inline CSS styles for the image.
- `loading`: This attribute indicates how the browser should load the image, with options such as "lazy" or "eager".

Example with additional attributes:
```html
<img src="image.jpg" alt="Image description" width="300" height="200" title="Click to enlarge" class="image-thumbnail" loading="lazy">
```

Remember to provide a meaningful `alt` text for accessibility, as it assists users with visual impairments and helps search engines understand the content of the image. The `width` and `height` attributes should reflect the actual dimensions of the image to prevent layout shifts and ensure proper rendering.

By using the `<img>` tag, you can easily add images to your webpages and customize their display to suit your design and content requirements.