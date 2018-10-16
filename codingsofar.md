# Code Work so far
The following code was written in Python 3
import turtle

wn=turtle.Screen()
wn.bgcolor("black")

turters = turtle.Turtle()


turters.speed(100)



for i in range(180):
    turters.forward(100)
    turters.right(30)
    turters.color("purple")
    turters.forward(20)
    turters.left(60)
    turters.forward(50)
    turters.right(30)
    turters.color("orange")

    turters.penup()
    turters.setposition(0, 0)
    turters.pendown()

    turters.right(2)

turtle.done()
