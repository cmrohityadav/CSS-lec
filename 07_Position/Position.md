# Position

## Static
- Default setting for all elements.
- Elements flow in the normal document layout, from top to bottom, left to right.
- <span style='color: red;'> No </span>top, right, bottom, or left properties apply in this mode.
## Relative
- The element remains in the normal flow, but you can use top, right, bottom, and left properties to move it relative to its original position.
- Space is still preserved for the element, even if it’s moved.


## Absolute

- The element is removed from the normal document flow.
- Positioned relative to the nearest positioned ancestor (an ancestor with position set to relative, absolute, or fixed). 
- If no such ancestor exists,<span style='color: red;'> it’s positioned relative to the <html> (or the browser viewport).</span>
Can use top, right, bottom, and left to position it precisely.

[?] When you apply position: absolute to an element without specifying top, right, bottom, or left, the element will be positioned based on its natural position within the nearest positioned ancestor. Here’s what this means:

- No Shift from Natural Position: Without top, right, bottom, or left values, the element stays in the same location it would have appeared in, but it no longer takes up space in the document flow.

- Positioned Ancestor Reference: If there is a positioned ancestor (an ancestor with position: relative, absolute, or fixed), the element will align with that ancestor as if it were positioned relative to it.

- No Positioned Ancestor: If there is no positioned ancestor, it will default to the <html> (viewport) and maintain its original place but removed from the flow.
## Fixed

- The element is removed from the document flow and positioned relative to the viewport.
- Stays in place when you scroll the page (useful for sticky headers, sidebars, etc.).
- Can be positioned using top, right, bottom, and left.


## Sticky

