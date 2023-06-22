# Margin

![Margin CSS](https://www.pntbrother.com/wp-content/uploads/2015/08/margin.jpg)

In CSS, the `margin` property is used to create space around an element. It defines the empty space outside the boundaries of an element. Margin can be applied to all four sides of an element (top, right, bottom, left), or individual sides can be targeted separately.

Here's the general syntax for using the `margin` property:

```css
selector {
  margin: value;
}
```

You can also specify different values for each side using the shorthand notation:

```css
selector {
  margin: top-value right-value bottom-value left-value;
}
```

The `value` can be specified in various units, such as pixels (`px`), percentages (`%`), ems (`em`), or rems (`rem`).

Here are some examples to illustrate the usage of the `margin` property:

```css
/* Apply equal margin to all sides */
.box {
  margin: 20px;
}

/* Apply different margins to each side */
.box {
  margin: 10px 20px 15px 30px;
}

/* Apply margin only to the top and bottom sides */
.box {
  margin: 10px 0;
}
```

In the first example, all sides of the `.box` element will have a margin of `20px`. In the second example, the top side will have a margin of `10px`, the right side `20px`, the bottom side `15px`, and the left side `30px`. In the third example, the top and bottom sides will have a margin of `10px`, while the right and left sides will have no margin (`0`).

You can adjust the values as needed to create the desired spacing around your elements using the `margin` property.