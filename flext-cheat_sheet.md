
Properties for flexbox container

**flex-direction: row | row-reverse | column | column-reverse**

It is possible to specify the direction your elements will follow. Traditionally text goes from left to right which is flex’s default setting however it can be set from right to left or even top to bottom. The four flex-direction are:

  **row : organized from left to right** 

**row-reverse: organized from right to left** 

**column: organized from top to bottom**

**column-reverse: organized from bottom to top.** 

**flex-wrap: wrap | nowrap**

The standard layout is to plot the elements from left to right in a straight line. The wrap feature allows you customize this to match the size of the window displaying the page. 

  **wrap: Automatically wrap the items with as the window space gets smaller.** 

**Nowrap: Default setting, items remain rigid and don’t respond  to adjustments made to the window size.**

**align-items: flex-start | flex-end | center |Stretch**

This determines how the flex items are to be positioned on the page. Items can be aligned in a variety of ways 

**Flex-start: Similar to standard writing, items start at the top left-hand corner and are positioned from left to right** 

 **Flex-end: Position begins in the bottom right hand corner.** 

    Center: Item is positioned from the center. 

    Stretch: item expands to fill the container. 

justify-content: flex-start | flex-end | center | space-between | space-evenly

Justify-content determines the alignment of the flex items. 

    Flex-start: goes from right to left along the main axis. 

    Flex-end: goes from left to right along the main axis. 

    Center: Starting at the middle, alignments expands from there. 

    Space-between: first and last item are flush with the left and right wall respectively, every other item is evenly spaced. 

    Space-evenly: each item is equidistant from each other and the boundary wall 

Properties for flexbox items (child)

flex-grow: factor of flex’s main size  

This attribute enables the flex container to grow proportionally to the other containers present. 

flex-shrink: factor of flex’s main size

This allows elements to shrink in relation to items around it.

flex-basis: auto | factor of main’s size | measurement unit

The sets the initial main size of an item. It can be overridden if other stylized elements are configured. 

order:position in flex /* Set ascending by default */

The standard positioning of items is by source order, however this feature will enable you to configure where the items appear on the page. 

align-self:  start | center | end | stretch

This determines where on the page the child items will be positioned. Similar to the main flex attributes, start is to the left and end is to the right.