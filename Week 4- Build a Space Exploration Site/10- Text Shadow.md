# Text Shadow

![BText Shadow](https://i7x7p5b7.stackpathcdn.com/codrops/wp-content/uploads/2014/12/text-shadow-syntax-img1.png?x11884)

In CSS, the `text-shadow` property is used to add a shadow effect to the text within an element. It allows you to create visually appealing text effects by adding a shadow behind the text. The `text-shadow` property takes multiple values to define the color, blur radius, and offset of the shadow.

Here's the syntax for the `text-shadow` property:

```css
selector {
  text-shadow: <horizontal-offset> <vertical-offset> <blur-radius> <color>;
}
```

- `<horizontal-offset>`: Specifies the horizontal distance of the shadow from the text. A positive value moves the shadow to the right, and a negative value moves it to the left.
- `<vertical-offset>`: Specifies the vertical distance of the shadow from the text. A positive value moves the shadow downwards, and a negative value moves it upwards.
- `<blur-radius>`: Determines the blurriness of the shadow. A larger value creates a more blurred shadow effect, while a value of `0` creates a sharp shadow.
- `<color>`: Sets the color of the shadow. This can be a named color, RGB value, hexadecimal value, or any valid CSS color notation.

Here's an example that demonstrates the usage of the `text-shadow` property:

```css
h1 {
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
```

In this example, the `<h1>` element will have a text shadow that is offset by 2 pixels horizontally and 2 pixels vertically from the text. The shadow has a blur radius of 4 pixels and a semi-transparent black color (`rgba(0, 0, 0, 0.5)`), creating a subtle shadow effect.

You can experiment with different values for `text-shadow` to achieve various text shadow effects. Multiple text shadows can also be applied to an element by separating them with commas.

```css
h1 {
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5), -2px -2px 4px rgba(255, 255, 255, 0.5);
}
```

In this example, two text shadows are applied to the `<h1>` element. The first shadow is black with a positive offset, and the second shadow is white with a negative offset, creating a contrasting shadow effect.

Remember to use `text-shadow` judiciously to ensure that the text remains legible and accessible to all users.