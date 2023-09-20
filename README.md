# 9-18-2023

### Information

Today we learned about shapes, well not shapes
but, how to code to create shapes using the
tools rasbery pi gave us. We used Mu since
replit didn't like what I inputed so, I couldn't really
do anything about that...

We then looked at the old computers and the old games
which were text based. One of these known as the oregon trail
was the most recognizable for me in general.

--------------

### Coding

I also did some coding to create a rectangle:

from shapes import Paper, Triangle, Oval, Rectangle

paper = Paper()

rect1 = Rectangle()

rect1.set_color("blue")
rect1.set_height(100)
rect1.set_width(200)



rect1.draw()

paper.display()

-------------

### Code from today

from shapes import Paper, Triangle, Oval, Rectangle

paper = Paper()

rect1 = Rectangle()

rect1.set_color("blue")
rect1.set_height(100)
rect1.set_width(200)
rect1.set_x(200)
rect1.set_y(200)

oval1 = Oval()


oval1.set_x(250)
oval1.set_y(200)
oval1.set_height(100)
oval1.set_width(100)
oval1.set_color("red")

tri1 = Triangle()

tri1.set_x(300)
tri1.set_y(150)
tri1.set_x(300)
tri1.set_y(150)
tri1.set_color("yellow")


rect1.draw()
tri1.draw()
oval1.draw()


paper.display()
