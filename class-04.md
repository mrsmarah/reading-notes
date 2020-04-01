# Grid css

- The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

**CSS Grid Layout**

- is a two-dimensional grid-based layout system that aims to do nothing less than completely change the way we design grid-based user interfaces.

-  CSS has always been used to lay out our web pages, but it’s never done a very good job of it. First, we used tables, then floats, positioning and inline-block, but all of these methods were essentially hacks and left out a lot of important functionality (vertical centering, for instance). 

- Flexbox helped out, but it’s intended for simpler one-dimensional layouts, not complex two-dimensional ones (Flexbox and Grid actually work very well together). 


**Grid Container**

- The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.

**Grid Item**

- The children (i.e. direct descendants) of the grid container. Here the item elements are grid items, but sub-item isn’t.

**Grid Line**

- The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. Here the yellow line is an example of a column grid line.

**Grid Track**

- The space between two adjacent grid lines. You can think of them like the columns or rows of the grid. Here’s the grid track between the second and third row grid lines.

**Properties for the Grid Container**

- display
- grid-template-columns
- grid-template-rows
- grid-template-areas
- grid-template
- grid-column-gap
- grid-row-gap
- grid-gap
- justify-items
- align-items
- place-items

**Properties for the Grid Items**

- grid-column-start
- grid-column-end
- grid-row-start
- grid-row-end
- grid-column
- grid-row
- grid-area