# FlexBoxDemo

* Notes 

# Display:
- 'display:flex' will move items along the main axis

# Flex-Direction:
- will define the main and cross axis
- flex-direction column will make the main axis vertical
- flex-direction row will make the main horizontal
- The flex direction is set horizontal by default, so rows is not necessary


# Justify-Content:
- flex-start will align items on left side of main axis
- flex-end will align items on right side of main axis
- center will aligns items in the middle
- space-between will evenly space the items until they fill the container
- space-around is similar to space-between, but will leave space on the edges of the items
- space-evenly will do the same thing as space around, but leaves the same space in between the edges and between items

# Align-items:
- same as above, but insteads aligns items on the cross axis

# Flex-Wrap:
- Items will try to squeeze as much as possible into the main axis
- 'flex-wrap: warp' will create a new row of items
- this unlocks the 'align-content' property

# Align-Content:
- This allows us to align everything on the cross axis
- reference justify-content for property key words

# Gap:
- This can be used to add gaps in between each items
- use 'em' 

# CSS Units of Measurement 

# 1 - Absolute Lengths:

- px (pixels): A pixel is a dot on the computer screen, and it's the smallest visible unit of measurement. However, its size can vary across devices and screens.
- pt (points): Traditionally used in print media, with 1pt equivalent to 1/72nd of an inch. It's often less useful on screens.

# 2 - Relative Lengths:

- em: This unit is relative to the font-size of its closest parent. If used to define font-size, it's relative to the font-size of the element itself.
- rem (root em): This is similar to em, but it's always relative to the root (or highest-level parent) element's font-size, usually the <html> element.
- vh (viewport height) and vw (viewport width): These are relative to the size of the user's viewport. 1vh is 1% of the viewport's height, and 1vw is 1% of the viewport's width.
- % (percent): This unit is relative to the size of the parent element.

# 3 - Flexible Lengths:

- fr (fractional units): This unit is used with CSS Grid to represent a fraction of the available space.