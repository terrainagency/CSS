# CSS

## Centering
Do not use flexbox to center horizontally, instead use `mx-auto`. Use flexbox for vertical centering.

## Z-Index
Whenever feasible, z-index should be managed by the order of the elements in the HTML structure. If the element has the `aria-hidden` attribute, then z-index should be avoided unless impossible via the structure of the greater document.
