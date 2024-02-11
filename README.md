import turtle

ben = turtle.Turtle()
turtle.bgcolor("black")
ben.width(3)
ben.color("turquoise")
ben.begin_fill()
ben.left(48)
ben.fd(200)
ben.circle(90, 200)
ben.left(50)
ben.circle(-90, -200)
ben.fd(-200)
ben.end_fill()
ben.color("white")
ben.write("I love Python ", move=False,
    align="center", font=("Arial", 50, "bold"))
turtle.done()
