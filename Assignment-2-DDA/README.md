# CGM Lab Assignment 2 - DDA Line Drawing Algorithm

## Aim
To implement the Digital Differential Analyzer (DDA) algorithm to draw a straight line between two given points using C++ graphics.

## Algorithm
1. Accept the starting point `(x1, y1)` and ending point `(x2, y2)`.
2. Calculate `dx = x2 - x1` and `dy = y2 - y1`.
3. Calculate `steps = max(abs(dx), abs(dy))`.
4. Calculate the x and y increments.
5. Generate intermediate points using the increments.
6. Plot each point using `putpixel()`.
7. Display the line in the graphics window.

## Technologies Used
- C++
- graphics.h (WinBGIm-compatible graphics environment)

## Files
- `dda_line.cpp` — Source code
- `dda_output.png` — Screenshot of the program output

## Learning Outcome
Learned how the DDA line drawing algorithm generates intermediate pixel coordinates to rasterize a straight line.
