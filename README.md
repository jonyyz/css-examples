# CSS Examples

## CSS Triangle Example

`css-triangle-example.html`

This example demonstrates how to build a tooltip box that has an arrow. In order to do this in CSS, I use the CSS Triangle trick where I have an element that has 0 height and width and set all borders to a specific width and then set them all transparent except for one. The one that isn't transparent will be the arrow. For example, the top border will be a down arrow and a right border will be a left arrow.

In this example, I wanted a border around both the tooltip border and arrow. In order to do this using the CSS triangle hack, you have to create another triangle that is slightly bigger that is the border color and position it underneath the other triangle to give it the look of a continuation of the border.

Another thing to keep in mind is that the first triangle whose background color matches the tooltip body has to be positioned such that it is on top of the bottom border of the body thus hiding it.

More info [here](https://css-tricks.com/snippets/css/css-triangle/).

## Layout Example

`layout-example.html`

This example demonstrates a layout such that there is a fixed header, footer and left navigation menu. Any content placed in the content pane will overflow and scroll, leaving everything else in place. If the navigation menu overflows it will also scroll.
