# Create print styles using CSS3 Media Queries

You can create print syles like this:

```css

@media print {
    /* Styles go here */
}
```

Print styles should be placed at the end of all your other styles. By doing so
they are given greater weight due to the CSS cascade and are less likely to be
over-written by other CSS rules.

This example show how to print the content of a table wich has a fixed height
and a vertical scroll bar.

If you want to learn more about CSS3 print styles, check out [this](https://benfrain.com/create-print-styles-using-css3-media-queries/) blogpost.
