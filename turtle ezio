import turtle 
import random
screen=turtle.screen()
screen.setup(800,800)
screen.bgcolour("white")
ezio=turtle.turtle
ezio.speed(0)
ezio.hideturtle()
turtle.tracer(0)
def draw_rhombus(x,y,side, angle,rotation,colour):
    ezio.penup()
    ezio.goto(x,y)
    ezio.setheading(rotation)
    ezio.pendown()
    ezio.fillcolour(colour)
    ezio.begin_fill()

    for j in range(2):
        ezio.forward(side)
        ezio.left(angle)
        ezio.forward(side)
        ezio.left(180-angle)

ezio.end_fill()
ezio.penup
for k in range (50):
    x= random.uniform(-300,-300)
    y= random.uniform(-300,-300)
    side= random.uniform(40,120)
    angle= random.uniform(30,150)
    rotation=random.uniform(0,360)
    color= (random.random(),random.random(),random.random())

    draw_rhombus(x,y,side,angle,rotation,color)
turtle.tracer
