#position: static;

####HTML elements are positioned static by default.

####Static positioned elements are not affected by the top, bottom, left, right, z-index properties.

##`zIndex()` returns 0

####An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

####This `<div>` element has position: static;
####Stacks down the Y-axis or is placed side by side on the same plane
##Example

```
div.static {
  position: static;
  border: 3px solid #333333;
}
```
![alt text](https://css-tricks.com/wp-content/csstricks-uploads/absolute-inside-relative2.png)
