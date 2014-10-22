AutoLayoutAndAlignmentExample
=============================

A sample Xcode 6 project which illustrates some Auto Layout and Alignment concepts as [an answer to a specific question on Stack Overflow](http://stackoverflow.com/questions/26505486/autolayout-alignment-constraints).

Highlights of the constraints that were created in this project include:

* Background View (Light purple) - Constraints pin the top, bottom, left and right sides to the edge of the parent view.
* Icon Container View (White) - Constraints pin the bottom, left and right sides; a height is also set which accommodates all of the icons.
* All image views have a width constraint and aspect ratio constraint (maintains equal width and height) and all labels are constrained to their appropriate image with the appropriate vertical constraint (top).
* The outside corner icons are all constrained only to their corner (top-left, top-right, bottom-left, bottom-right). The center corners are constrained to be centered horizontally inside the view.
