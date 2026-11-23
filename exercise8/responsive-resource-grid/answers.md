# CSS Grid and media queries: my answers

## 1. Which element is the grid container on this page?

The .resource-grid is the grid container because it holds all the cards.

## 2. Which elements are the grid items?

The five `<article class="resource-card">` elements are the grid items inside the .resource-grid.

## 3. What does `1fr` mean in this grid?

1fr means one equal part of the available space. It makes the columns share the space equally.

## 4. Why does the highlighted card need a reset in the phone media query?

Because the highlighted card takes up two columns on a bigger screen. On a phone, it needs to change back to one column so it fits properly.

## 5. Why must you test the same page at more than one width of the browser window?

To make sure the page looks good on both big and small screens.

## 6. Which change did you make? What changed in the browser, and which CSS property or media query caused it?

I changed the grid to show three columns on a big screen, two on a tablet, and one on a phone. The media queries made this happen.