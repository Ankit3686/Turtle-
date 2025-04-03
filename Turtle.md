# Turtle
Turtle Library in Python
The turtle library is a popular Python module for introducing programming and graphics. It provides a fun, interactive way to create drawings and shapes using a virtual "turtle" that moves around the screen.

Common Turtle Methods

Movement
forward(distance) or fd(distance) - Move forward
backward(distance) or bk(distance) - Move backward
right(angle) or rt(angle) - Turn right
left(angle) or lt(angle) - Turn left
goto(x, y) or setpos(x, y) - Move to specific coordinates
setx(x) - Set x coordinate
sety(y) - Set y coordinate

Pen Control
penup() or pu() - Lift the pen (stop drawing)
pendown() or pd() - Lower the pen (start drawing)
pensize(width) - Set line thickness
pencolor(color) - Set pen color
fillcolor(color) - Set fill color
begin_fill() - Start filling a shape
end_fill() - End filling a shape

Turtle State
speed(speed) - Set animation speed (0-10, 0 is fastest)
hideturtle() - Make turtle invisible
showturtle() - Make turtle visible
isvisible() - Check if turtle is visible
position() or pos() - Get current position
heading() - Get current heading angle
setheading(angle) - Set heading angle
