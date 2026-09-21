# LeetCode 223 - Rectangle Area

## Problem Description

Given two rectangles in a 2D plane, find the total area covered by the two rectangles.

The rectangles may overlap, so the overlapping area must be counted only once.

## Example

**Input:**

```text
ax1 = -3, ay1 = 0, ax2 = 3, ay2 = 4
bx1 = 0, ay1 = -1, bx2 = 9, by2 = 2
```

**Output:**

```text
45
```

## Approach

First calculate the area of both rectangles separately.

If the rectangles overlap, calculate the width and height of the overlapping region and subtract its area once.

```text
Total Area = Area1 + Area2 - Overlap Area
```

## Algorithm

1. Calculate the area of the first rectangle.
2. Calculate the area of the second rectangle.
3. Find the overlapping width.
4. Find the overlapping height.
5. Calculate the overlapping area.
6. Subtract the overlap from the sum of both rectangle areas.
7. Return the result.

## Time Complexity

`O(1)`

## Space Complexity

`O(1)`

## Key Concepts

* Geometry
* Rectangle Area
* Coordinate System
* Overlapping Regions
* Math

## Author

T.nandhini
