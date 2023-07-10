# FlexBoxDemo Notes

## Display Property

- `display: flex;` This will arrange items along the main axis.

## Flex-Direction Property

- Defines the main and cross axis.
- `flex-direction: column;` The main axis becomes vertical.
- `flex-direction: row;` The main axis becomes horizontal (this is the default setting, so `row` is not always necessary).

## Justify-Content Property

- `justify-content: flex-start;` Aligns items to the left side of the main axis.
- `justify-content: flex-end;` Aligns items to the right side of the main axis.
- `justify-content: center;` Aligns items in the middle of the main axis.
- `justify-content: space-between;` Distributes items evenly along the main axis, without space at the edges.
- `justify-content: space-around;` Similar to `space-between`, but with space at the edges.
- `justify-content: space-evenly;` Distributes items and space evenly, including the edges.

## Align-Items Property

- Aligns items on the cross axis, similar to `justify-content`.

## Flex-Wrap Property

- Items will try to fit into the main axis as much as possible.
- `flex-wrap: wrap;` Creates a new row of items, and this unlocks the `align-content` property.

## Align-Content Property

- Allows alignment of items on the cross axis. Use the same keywords as in `justify-content`.

## Gap Property

- Used to add gaps between each item. Requires a unit of measurement as a value.

## CSS Units of Measurement 

### 1 - Absolute Lengths:

- `px` (pixels): A pixel is a dot on the computer screen, and it's the smallest visible unit of measurement. However, its size can vary across devices and screens.
- `pt` (points): Traditionally used in print media, with 1pt equivalent to 1/72nd of an inch. It's often less useful on screens.

### 2 - Relative Lengths:

- `em`: This unit is relative to the font-size of its closest parent. If used to define font-size, it's relative to the font-size of the element itself.
- `rem` (root em): This is similar to `em`, but it's always relative to the root (or highest-level parent) element's font-size, usually the `<html>` element.
- `vh` (viewport height) and `vw` (viewport width): These are relative to the size of the user's viewport. `1vh` is 1% of the viewport's height, and `1vw` is 1% of the viewport's width.
- `%` (percent): This unit is relative to the size of the parent element.

### 3 - Flexible Lengths:

- `fr` (fractional units): This unit is used with CSS Grid to represent a fraction of the available space.

## Flex-grow Property

- `flex-grow: 1;` Allows the item to grow if there is enough space to do so.

## Flex-Shrink Property

- `flex-shrink: 0;` Prevents the item from shrinking when the container is collapsed.
- `flex-shrink` values above 0 will cause the item to shrink to a given size (relative to the value) when the container is collapsed.

## Flex-Basis Property

- Overrides the width of an item.

## Align-Self Property

- This is used when you want to adjust the placement of a single item inside of a container.


