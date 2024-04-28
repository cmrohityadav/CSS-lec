# Position
## position: static
- This is the default position value for all elements.
- Elements with position: static; are positioned according to the normal flow of the document.
- The top, right, bottom, and left properties have no effect on statically positioned elements.
## position: relative;
- Elements with position: relative; are positioned relative to their normal position in the document flow.
- When you use top, right, bottom, or left properties with position: relative;, the element is shifted from its original position by the specified amount.
- However, the space the element originally occupied in the document flow is still reserved.
## position: absolute;
- Elements with position: absolute; are positioned relative to the nearest positioned ancestor (an ancestor with a position value other than static) or to the initial containing block if no positioned ancestor is found.
- An absolutely positioned element is taken out of the normal document flow, meaning it doesn't affect the positioning of other elements and other elements don't affect its position.
- The top, right, bottom, and left properties are used to specify the position of the element relative to its containing block.
##  position: fixed;
Elements with position: fixed; are positioned relative to the viewport (the browser window).
They remain fixed at their specified position even when the page is scrolled.
- Fixed-positioned elements are removed from the normal document flow, similar to absolutely positioned elements.
- Like absolutely positioned elements, the top, right, bottom, and left properties are used to specify the position of the element relative to the viewport.
## position: sticky;
Elements with position: sticky; are positioned based on the user's scroll position.
They behave like position: relative; until a specified scroll point is reached, then they "stick" to a specific position within their containing block.
Once the user scrolls past the specified point, the element behaves like position: fixed;, sticking to its position until the end of the containing block is reached.
Sticky positioning is often used for creating sticky headers, navigation bars, or sidebars.