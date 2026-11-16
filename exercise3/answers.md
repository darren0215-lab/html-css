# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?

To select specific elements witout affecting others.

## 2. What does the space mean in `.material-shelf p`?

It selects all `<p>`inside .material-shelf.

## 3. What does `>` mean in `.quick-nav > a`?

It selects only direct child links

## 4. Why must a button link have a `:hover` style and a `:focus` style?

:hover shows when the mouse moves over it.
:focus shows when the user selects it using a keyboard.

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?

.quick-nav >a wins because it is more specific.