# CLASS 8 READING NOTES


**Flexbox is designed for one-dimensional content. Explain what that means.**

“When a flex container wraps it creates multiple flex lines. In terms of space distribution, each line acts like a new flex container. Therefore if you are wrapping rows, it is not possible to get something in row 2 to line up with something above it in row 1. This is what is meant by flexbox being one-dimensional. You can control alignment in one axis, a row or a column, not both together as we can do in grid”.



**Explain the difference between the main axis and the cross axis.**


The main axis is the one set by the flex-directory property. If that is a row, your main axis is along the row, if it is a column, your main axis is along the column. The cross axis therefore is the perpendicular line to the main axis.


**How can using certain properties of flexbox negatively impact accessibility?**

When using the ‘row-reverse’ or ‘column-reverse’ to reorder the visual display, the reordering only happens to the visual order, regardless of how things are ordered in HTML. Screen readers will read the logical order, which is the HTML one. 



**What are some advantages of using flexbox over float?**

1. You can vertically center a block of contentment inside of its parent.
2. You can make all the children of a container take up an equal amount of available width/height, regardless of how much width/height is available.
3. You can make all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.


**How does this topic connect with the long term goals?**

This is actually the first piece of information I included in ‘things I want to know more about’, which was ‘learn how to place images exactly where I want with CSS’. Seems like I got my answer. Learning how to use flexbox will allow me to place elements in the desired place without expanding the margin, which is what I am doing right now.