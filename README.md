# Computer-Graphics
SEIT/SPPU

Digital Differential Analyzer Algorithm

The DDA (Digital Differential Analyzer) line drawing algorithm creates a line segment between two predetermined endpoints in computer graphics. It is a straightforward and effective approach that plots the line by using the incremental difference between the x- and y-coordinates of the two ends.
The following steps make up the DDA line generating algorithm:
1->Enter (x1,y1) and (x2,y2), the line segment's two endpoints.
2->Calculate dx and dy, respectively, to represent the difference between the endpoints' x- and y-coordinates.
3->As m = dy/dx, determine the line's slope.
4->(X1,Y1) should be chosen as the line's starting point.
5->Using a loop that increments the line's x-coordinates by one each time, determine the associated y-coordinate using the formula y = y1+ m(x – x1).
6->Place the calculated (x,y) coordinate on a plot for the pixel.
7->Up until the endpoint (x2,y2) is reached, repeat steps 5 and 6 as needed.
The DDA technique is appropriate for real-time applications since it is computationally effective and relatively simple to implement. It can't support vertical lines, for example, and some computers may find floating-point arithmetic to be slow. These are only a few of its drawbacks.

