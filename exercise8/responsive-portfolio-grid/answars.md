# Responsive portfolio grid: my answers

## 1. Which element became the grid container?

The .project-grid became the grid container because it holds all the project cards.

## 2. Which elements became the grid items?

The five `<article>` elements with the project-card class are the grid items. 

## 3. Which rule makes the columns for wide screens?

The grid-template-columns: repeat(4, 1fr); makes four equal columns.

## 4. Which rule changes the layout for a browser window of medium width?

The @media (max-width: 820px) changes the grid to two columns.

## 5. Which rule stops the featured card from making the phone layout too wide?

The grid-column: auto; resets the featured card to one column on small screens.