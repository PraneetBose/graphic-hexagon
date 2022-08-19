# graphic-hexagon
# Python program to draw
# Spiral Helix Pattern
# using Turtle Programming

# Python program to draw
# Rainbow Benzene / hexagon
# using Turtle Programming
import turtle
colors = ['red', 'purple', 'blue', 'green', 'orange', 'yellow']
t = turtle.Pen()
turtle.speed(80)
turtle.bgcolor('black')
for x in range(180):
	t.pencolor(colors[x%6])
	t.width(x//100 + 1)
	t.forward(x)
	t.left(59)
for i in range(100):
    turtle.circle(5 * i)
    turtle.circle(-5 * i)
    turtle.left(i)

turtle.exitonclick()
Footer
