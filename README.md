# python_turtle
Examples of python turtle

EXAMPLE 1 - DRAW A SQUARE

#CODE

#Step 1: import turtle
import turtle

#Step 2: Create a turtle.  We will call it "t"
t = turtle.Turtle()

#Step 3: Draw the thing
t.forward(50) #length
t.right(90) #angle

t.forward(50)
t.right(90) 

t.forward(50)
t.right(90) 

t.forward(50)
t.right(90)

#Step 4: Run the turtle
t.done()


#EXAMPLE 2 - DRAWING A SQUARE USING LOOPS
#Step 1: import turtle
import turtle

#Step 2: Create a turtle.  We will call it "t"
t = turtle.Turtle()

#Step 3: Draw the thing
for i in range(4):
  t.forward(50) #length
  t.right(90) #angle
#Step 1: import turtle
import turtle

#Step 2: Create a turtle.  We will call it "t"
t = turtle.Turtle()

#Step 3: Draw the thing
def square(length , angle):
  for i in range(4):
    t.forward(100) #length
    t.right(90) #angle

for i in range(200):
  square(100,90)
  t.right(5)
#Step 4: Run the turtle
t.done()



EXAMPLE 4 - DRAWING A STAR
import turtle 

star = turtle.Turtle()

for i in range(5):
    star.forward(100)
    star.right(144)
    
turtle.done()


EXAMPLE 5 - SPIRALING STAR
import turtle 

spiral = turtle.Turtle()

for i in range(20):
    spiral.forward(i * 10)
    spiral.right(144)
    
turtle.done()


EXAMPLE 6 - CHANGING SHAPES COLOR
import turtle 

color = turtle.Turtle()

color.pencolor("blue")
for i in range(100):
    painter.forward(100)
    painter.left(123) 
        
turtle.done()
#Step 4: Run the turtle
t.done()


#EXAMPLE 7 - SQUARE OF SQUARES
import turtle             
my_pen = turtle.Turtle()
my_pen.color("black")
def my_sqrfunc(size):
   for i in range(4):
      my_pen.fd(size)
      my_pen.left(90)
      
my_sqrfunc(146)
my_sqrfunc(126)
my_sqrfunc(106)
my_sqrfunc(86)
my_sqrfunc(66)
my_sqrfunc(46)
my_sqrfunc(26)


EXAMPLE 8 - COLORFUL SPIRAL
import turtle             
colors = [ "red","purple","blue","green","orange","yellow"]
my_pen = turtle.Pen()
turtle.bgcolor("black")
for x in range(360):
   my_pen.pencolor(colors[x % 6])
   my_pen.width(x/100 + 1)
   my_pen.forward(x)
   my_pen.left(59)
